---
title: Project
excerpt: Project Enviroments
sections:
  - section_id: hero
    type: section_hero
    title: Schnellschuss
    subtitle: '### Hosted enviroments at fingertips'
    image: images/avatar.png
  - title: Text
    section_id: intro
    type: section_content
    content: >
      ### Project Enviroments


      We also give you the option to keep *shots* running in the background and
      connect to them later on again. The system stays fully active in the
      background. Also we offer the possibility to save the current state of the
      *shot* as a image and create a new *shot* at any given time from this
      state. This is similiar to shutting down and start your local computer -
      with the addition of cloning your harddrive to another computer!


      Especially the image-function makes it possible to have your own dedicated
      and isolated project enviroment in the cloud - instantiated and ready in
      under **9 seconds**. 


      #### Some use cases


      - Quickly instantiate your personal picture-backup image, upload the
      latest pictures via the hosted web-app you installed yourself earlier
      (like Nextcloud). Save the state and put it to sleep again.


      - Create an webserver enviroment to show the latest progress of your
      webapp to your friends. Instantiate a *shot* from your configured image,
      upload the updated files and your ready to show off!


      - Working on larger and more time intensive projects, like configuring a
      mailserver or a specific software enviroment. Save the image, go to sleep
      and put everythign up again in the morning!


      #### Examples


      ##### Create a project shot


      ```console

      [fafre@fafre-20hn002vge ~]$ schnellschuss new project

      Created new shot with IPv4: 192.168.1.1 IPv6: ::ffff:c0a8:101

      root@ss-36dj9:~# touch newconfig.json

      root@ss-36dj9:~# exit

      Project hasn't been saved! Enter image name to save: test-project

      Shutting down shot...

      Creating image...

      [fafre@fafre-20hn002vge ~]$

      ```
layout: advanced
---
