---
# Leave the homepage title empty to use the site title
title: Experience
date: 2024-03-25
type: landing

sections:

  - block: hero
    content:
      title: |
        <span style="font-size:75%">About My Personality</span>
      image:
        filename: 내mbti.png # Change to the desired image filename
      text: |
        <br>
        <span style="font-size:80%">I created this page to share a bit more about myself.
        <br>As you can see from my MBTI test results, I am a highly introverted and extremely realistic person. I act based on logic and planning rather than emotions, and even when it comes to spending, I prefer to make careful and thoughtful decisions rather than acting impulsively.
        <br>Being an ISTJ and having similarities with ESTJ personalities, I am proud of my ISTJ personality as both types are known to manage their finances well.
        <br>
        <br>Additionally, as a representative of introverts at Chonbuk National University, I strive to uphold the interests of introverts.</span>

    design:
      height: '400px' # Adjust the height of the banner as needed (px value can be changed)

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">Here's a brief introduction to my experiences working on freelance projects.</span>

  - block: slider
    content:
      slides:

      # 1. MBTI Test Site
      - title: <span style="font-size:90%">MBTI Test Site</span>
        content: <span style="font-size:90%">A site where you can take psychological tests. Initially created to earn advertising revenue through Google AdSense, but it's now generating income through freelancing.</span>
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
        content: <span style="font-size:90%">A site for learning English that I revised and redeveloped.</span>
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
        content: <span style="font-size:90%">Contributed to developing and revising specific functionalities of a shopping mall site.</span>
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
        content: <span style="font-size:90%">Developed the admin page for the frontend part of a shopping mall site.</span>
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

      # 5. React Native Push Notification Freelancing
      - title: <span style="font-size:90%">React Native Push Notification Freelancing</span>
        content: <span style="font-size:90%">Assisted in integrating push notifications in a React Native app using Firebase.</span>
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
