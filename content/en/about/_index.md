---
# Leave the homepage title empty to use the site title
title: Experience
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">Here is a brief introduction to the experiences and projects completed as part of freelancing work.</span>

  - block: slider
    content:
      slides:

      # 1. MBTI Test Site
      - title: <span style="font-size:90%">MBTI Test Site</span>
        content: <span style="font-size:90%">A website where users can take a psychological test. Initially created for Google AdSense revenue, it is currently earning through freelance projects.</span>
        align: center
        background:
          image:
            filename: mbti.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: external-link-alt
          icon_pack: fas
          text: <span style="font-size:60%">Visit</span>
          text-color: '#fff'
          url: https://supermbti.netlify.app/
          style: "transition: background-color 0.3s ease; background-color: #007BFF; color: #fff;"
          hover_style: "background-color: #FFD700;"


      # 2. English Learning Site
      - title: <span style="font-size:90%">English Learning Site</span>
        content: <span style="font-size:90%">An English learning website that I modified and redeveloped.</span>
        align: center
        background:
          image:
            filename: 영어사이트.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: external-link-alt
          icon_pack: fas
          text: <span style="font-size:60%">Visit</span>
          text-color: '#fff'
          url: https://abceggs.co.kr/

      # 3. Shopping Mall Site
      - title: <span style="font-size:90%">Shopping Mall Site</span>
        content: <span style="font-size:90%">I contributed to creating and modifying some features of this shopping mall site.</span>
        align: center
        background:
          image:
            filename: 쇼핑스팟.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: external-link-alt
          icon_pack: fas
          text: <span style="font-size:60%">Visit</span>
          text-color: '#fff'
          url: https://www.shospot.kr/

    

      # 4. Shopping Mall Admin Page
      - title: <span style="font-size:90%">Shopping Mall Admin Page</span>
        content: <span style="font-size:90%">I developed the admin page for the shopping mall's frontend.</span>
        align: center
        background:
          image:
            filename: 관리자.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: external-link-alt
          icon_pack: fas
          text: <span style="font-size:60%">Visit</span>
          text-color: '#fff'
          url: https://temp1234aa.netlify.app/back-end/

      # 5. Push Notification in React Native
      - title: <span style="font-size:90%">Push Notifications in React Native</span>
        content: <span style="font-size:90%">Assisted with integrating push notifications in a React Native app using Firebase.</span>
        align: center
        background:
          image:
            filename: 리액트외주.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
---