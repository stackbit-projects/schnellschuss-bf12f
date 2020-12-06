---
title: Home
excerpt: lorem-ipsum
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
      ### Session sharing


      *Schnellschuss* offers you two ways how you can conenct to your *shot*:


      1. Shared secure end-to-end connection

      2. Direct secure and private end-to-end conenction 


      You can freely chose your connection method, depending on your needs.


      #### Shared connection


      With the shared connection you have the possibility to work together with
      friends or colleagues at the same time in the same session! See this as
      the terminal-version of TeamViewer!


      - Decide if you want to share read and additionally write access to your
      session and share the conenction link or Id. And watch at the same *shot*
      in real-time.

      - You are able to record your session and use it later on as a
      documentation or create an interactive Tutorial from!

      - Instantly stream your *shot* output during a presentation, course,
      webcast, or programming stream! See this as Twitch for your Terminal.


      #### Examples


      ##### Share with friend


      ```console

      [fafre@fafre-20hn002vge ~]$ schnellschuss new disposable

      Created new shot with IPv4: 192.168.1.1 IPv6: ::ffff:c0a8:101

      root@ss-36dj9:~# echo hello from shot

      hello from shot

      root@ss-36dj9:~# schnellschuss share

      Your session Id is 293ad5ad-0d10-45e3-b1fa-328bf90c8be1

      root@ss-36dj9:~# 

      ```


      ```console

      [friend@fafre-20hn002vge ~]$ schnellschuss join
      293ad5ad-0d10-45e3-b1fa-328bf90c8be1

      Joined shot with IPv4: 192.168.1.1 IPv6: ::ffff:c0a8:101

      root@ss-36dj9:~# echo hello from shot

      hello from shot

      root@ss-36dj9:~# schnellschuss share

      Your session Id is 293ad5ad-0d10-45e3-b1fa-328bf90c8be1

      root@ss-36dj9:~# 

      ```
layout: advanced
---
