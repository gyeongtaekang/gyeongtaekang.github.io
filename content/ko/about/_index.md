---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">했던 프로젝트랑 간략히 소개</span>

  - block: slider
    content:
      slides:

      # 1. MBTI 검사 사이트
      - title: <span style="font-size:90%">MBTI 검사 사이트</span>
        content: <span style="font-size:90%">심리검사 테스트를 해볼 수 있는 사이트입니다. 구글 애드센스로 광고 수입을 받기 위해 만들었으나, 현재는 외주로 수익을 내고 있습니다.</span>
        align: center
        background:
          image:
            filename: mbti.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: external-link-alt
          icon_pack: fas
          text: <span style="font-size:60%">바로가기</span>
          text-color: '#fff'
          url: https://mbtitest.com

      # 2. 영어 학습 사이트
      - title: <span style="font-size:90%">영어 학습 사이트</span>
        content: <span style="font-size:90%">제가 수정하고 재개발한 영어 학습 사이트입니다.</span>
        align: center
        background:
          image:
            filename: english.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: external-link-alt
          icon_pack: fas
          text: <span style="font-size:60%">바로가기</span>
          text-color: '#fff'
          url: https://englishlearning.com

      # 3. 쇼핑몰 사이트
      - title: <span style="font-size:90%">쇼핑몰 사이트</span>
        content: <span style="font-size:90%">쇼핑몰 사이트의 일부 기능을 수정하고 제작하였습니다.</span>
        align: center
        background:
          image:
            filename: shopping.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: external-link-alt
          icon_pack: fas
          text: <span style="font-size:60%">바로가기</span>
          text-color: '#fff'
          url: https://shoppingmall.com

      # 4. 기존 슬라이더 - 전과
      - title: <span style="font-size:90%">2022/02/15 전북대학교 의류학과 -> 컴퓨터공학부로 전과</span>
        content: <span style="font-size:90%">전공을 의류학과에서 컴퓨터공학부로 전과한 것은 큰 전환점이며, 현재의 연구 및 활동 방향에 큰 영향을 준 중요한 사항입니다.</span>
        align: center
        background:
          image:
            filename: Ai.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      # 5. 기존 슬라이더 - 해커톤 최우수상
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

      # 6. 기존 슬라이더 - 메이커톤 베스트 피칭상
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
