---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">최근 5년간 일어난 저의 큰 이벤트들을 소개하겠습니다.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">2022/02/15 전북대학교 의류학과 -> 컴퓨터공학부로 전과</span>
        content: <span style="font-size:90%">전공을 의류학과에서 컴퓨터공학부로 전과한 것은 큰 전환점이며, 현재의 연구 및 활동 방향에 큰 영향을 준 중요한 사항입니다.<span style="font-size:90%">
        align: center
        background:
          image:
            filename: Ai.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">(2023/12/01~03) 전북대학교 아이디어 해커톤 최우수상</span>
        content: <span style="font-size:90%">아이디어 해커톤에서 최우수상을 받은 것은 창의성과 문제 해결 능력을 인정받은 중요한 성과입니다.</span>
        align: center
        background:
          image:
            filename: medical.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">2024/02/02 창업 아이디어 메이커톤 베스트 피칭상</span>
        content: <span style="font-size:90%">창업 아이디어 메이커톤에서 베스트 피칭상을 수상한 것은 아이디어의 사업화 가능성과 발표 능력을 인정받은 핵심 성과입니다.</span>
        align: center
        background:
          image:
            filename: healthcare.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">2024년 4월~ing 이경수 교수님 의료 인공지능 연구실</span>
        content: <span style="font-size:90%">현재 의료 인공지능 연구실에서 연구를 진행하고 있는 것은 컴퓨터공학 및 AI 분야의 전문성을 보여주는 중요한 활동입니다.</span>
        align: center
        background:
          image:
            filename: aerospace.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">2024/06/17~2024/07/10 내가 만드는 비교과 프로그램 공모전 우수상</span>
        content: <span style="font-size:90%">비교과 프로그램 공모전에서 우수상을 수상한 것은 다양한 프로그램 개발 능력을 인정받은 중요한 경험입니다.</span>
        align: center
        background:
          image:
            filename: contents.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Mathematics</span>
        content: <span style="font-size:90%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Development</span>
        content: <span style="font-size:90%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'


      - title: <span style="font-size:90%">Recruit</span>
        content: <span style="font-size:90%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: recruitment.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  # - block: hero
  #   content:
  #     title: |
  #       <span style="font-size:75%">Medical AI & Computational Science (MACS) Lab</span>
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       <span style="font-size:75%">전북대학교 의료 AI 및 계산 수학 연구실 (MACS Lab) 홈페이지에 오신 것을 환영합니다. MACS에서는 의료, 항공, 국방 분야에 AI 및 딥러닝을 활용한 연구를 수행하고 있으며, 의료 수학 및 AI 기반 연구도 함께 수행하고 있습니다. 뿐만 아니라, 풀스택 개발 및 AI를 활용한 어플리케이션 개발 등 Development & Deploy하는 실용적인 분야에도 집중하고 있습니다.</span>
  
---