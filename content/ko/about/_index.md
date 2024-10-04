---
# Leave the homepage title empty to use the site title
title: 경험
date: 2024-03-25
type: landing

sections:

  - block: hero
    content:
      title: |
        <span style="font-size:75%">나의 성격 소개</span>
      image:
        filename: 내mbti.jpg # 원하는 이미지 파일명으로 변경하세요
      text: |
        <br>
        <span style="font-size:80%">저에 대해 조금더 알려드리기 위해 이 페이지를 만들었습니다.
        <br>저는 MBTI 검사 결과를 보시는거 처럼 매우 내향적인 성격이며, 극도로 현실적입니다. 감정에 휘둘리지 않고 계획적으로 행동하며, 소비할 때도 충동적이기보다 신중하게 계획하고 실행하는 편입니다.</span>
    design:
      height: '400px' # 배너의 높이를 조절할 수 있습니다 (px 값 변경 가능)

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

      # 4. 쇼핑몰 관리자페이지
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

      # 5. 리액트 네이치브 푸쉬알림 보내기 외주
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

---
