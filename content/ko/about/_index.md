---
# Leave the homepage title empty to use the site title
title: 경험
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">외주와 함께 진행했던 경험을 간략하게 소개해드리겠습니다.</span>

  - block: slider
    content:
      slides:

      # 1. MBTI 검사 사이트
      - title: <span style="font-size:90%">MBTI 검사 사이트</span>
        content: <span style="font-size:90%">심리검사 테스트를 해볼 수 있는 사이트입니다. 구글 애드센스로 광고 수입을 받기 위해 만들었으나, 현재는 외주로 수익을 내고 있습니다.</span>
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
          text: <span style="font-size:60%">바로가기</span>
          text-color: '#fff'
          url: https://supermbti.netlify.app/
          style: "transition: background-color 0.3s ease; background-color: #007BFF; color: #fff;"
          hover_style: "background-color: #FFD700;"


      # 2. 영어 학습 사이트
      - title: <span style="font-size:90%">영어 학습 사이트</span>
        content: <span style="font-size:90%">제가 수정하고 재개발한 영어 학습 사이트입니다.</span>
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
          text: <span style="font-size:60%">바로가기</span>
          text-color: '#fff'
          url: https://abceggs.co.kr/

      # 3. 쇼핑몰 사이트
      - title: <span style="font-size:90%">쇼핑몰 사이트</span>
        content: <span style="font-size:90%">쇼핑몰 사이트의 일부 기능을 수정하고 제작하였습니다.</span>
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
          text: <span style="font-size:60%">바로가기</span>
          text-color: '#fff'
          url: https://www.shospot.kr/

    

      - title: <span style="font-size:90%">쇼핑몰 관리자페이지</span>
        content: <span style="font-size:90%">쇼핑몰 사이트 프론트부분중 관리자 페이지를 제작하였습니다</span>
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
          text: <span style="font-size:60%">바로가기</span>
          text-color: '#fff'
          url: https://temp1234aa.netlify.app/back-end/

      # 6. 기존 슬라이더 - 메이커톤 베스트 피칭상
      - title: <span style="font-size:90%">리액트 네이치브 푸쉬알림 보내기 외주</span>
        content: <span style="font-size:90%">리액트 네이티브앱에서 파이어베이스와 연동해서 푸쉬 앱알림을 도와드렸습니다.</span>
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
