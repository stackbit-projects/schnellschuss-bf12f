---
title: Disposable
excerpt: Overview
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
      ### Disposable enviroments


      #### Testing 


      You like to try out new things, want to quickly check how different
      configurations behave, or just want to make your new webapp accessible to
      give your friends a look? At the same time you don't want to mess up your
      lokal system?


      We got the right thing for you!


      *Shots* are bringing several benefits compared to local testing
      enviroments:


      - Every enviroment does have it's own puplic and dedicated IP-address -
      enabling friends and colleagues to e.g. connect to your test enviroment
      and give you a feedback about the website you just created. It's a real
      server!

      - Local enviroments produce a lot of waste and may slow down your system
      if not taken care of. Just leave the cleanup to us! Every testing
      enviroment is disposed after disconencting from it (only if you wish so!
      See [Project enviroments](#project enviroments)).


      Of course **Docker** is also available and pre-installed on our *shots* -
      possible faster instantiated due to our fast ehernet conenction. 


      #### Compensating bad bandwith


      Working with large files is a mess! Especially if you have to share the
      WiFi with Netflix addicts, or working from coffee shops.

      Extracting this config-file out of your Backup, or checking the output of
      this new machine learning model can escalate to a long lasting and
      frustrating journey.


      Every *shot* is providing you with a **1Gbit** (up/download with up to
      120MB/s) private enviroment, created in under **9 seconds**. Freshly
      created on every creation. Just piping console in- and output to your
      device!


      #### Examples


      ##### Create a disposable test shot


      ```console

      [fafre@fafre-20hn002vge ~]$ schnellschuss new disposable

      Created new shot with IPv4: 192.168.1.1 IPv6: ::ffff:c0a8:101

      root@ss-36dj9:~# echo hello from shot

      hello from shot

      root@ss-36dj9:~# exit

      Shot has been disposed

      [fafre@fafre-20hn002vge ~]$

      ```


      ##### Resume a shot


      This only works when you connect via a shared conenction.


      ```console

      [fafre@fafre-20hn002vge ~]$ schnellschuss new disposable --name
      resume-test --shared

      Created new shot "resume-test" with IPv4: 192.168.1.1 IPv6:
      ::ffff:c0a8:101

      root@resume-test:~# export x=shot

      root@resume-test:~# echo $x

      shot

      root@resume-test:~# exit --keep-alive

      Shot has been put to background

      [fafre@fafre-20hn002vge ~]$ echo $x


      [fafre@fafre-20hn002vge ~]$ schnellschuss resume resume-test

      Shot "resume-test" resumed with IPv4: 192.168.1.1 IPv6: ::ffff:c0a8:101

      root@resume-test:~# echo $x

      shot

      root@resume-test:~#

      ```
layout: advanced
---
