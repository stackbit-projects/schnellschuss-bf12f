---
title: Images
excerpt: Images
sections:
  - section_id: hero
    type: section_hero
    title: Schnellschuss
    subtitle: '### Virtual enviroments at fingertips'
    image: images/avatar.png
  - title: Text
    section_id: intro
    type: section_content
    content: >
      ### Images


      We already told you how you can use images for project enviroments in the
      [Project Enviroments section](#project enviroments). Now we tell you more
      details about it.


      #### Flexibility


      At any time you can clone your image and see how it performs with a
      changed configuration or middleware. See this a s a branch of your GitHub
      Repositiory for your *shot*!


      You can create an unlimited amount of instances from your image 


      #### Sharing is caring


      It's possible to share your private images with your friends - see this as
      a fork of your GitHub repository for your *shot*!


      This makes it easy to work together on server projects with your friends,
      colleagues or even the *Schnellschuss* community.


      #### Make it permanent


      Once you finished your project, we offer you to host the image on a real
      virtual or dedicated server, putting you into production with just one
      command!


      #### Examples


      ##### Resume a project shot from image


      ```console

      [fafre@fafre-20hn002vge ~]$ schnellschuss new project --from-image
      test-project

      Created new shot with IPv4: 192.168.1.1 IPv6: ::ffff:c0a8:101

      root@ss-36dj9:~# rm newconfig.json

      root@ss-36dj9:~# exit

      Project hasn't been saved! Enter image name to save:
      test-project-without-config

      Shutting down shot...

      Creating image...

      [fafre@fafre-20hn002vge ~]$

      ```


      ##### Create a shot from docker container


      ```console

      [fafre@fafre-20hn002vge ~]$ schnellschuss new disposable --from-docker
      ubuntu:latest

      Created new shot with IPv4: 192.168.1.1 IPv6: ::ffff:c0a8:101

      root@ss-36dj9:~# docker run -it ubuntu:latest

      root@6bd5be2ae8dc:/# exit

      root@ss-36dj9:~# exit

      Shot has been disposed

      [fafre@fafre-20hn002vge ~]$

      ```
layout: advanced
---
