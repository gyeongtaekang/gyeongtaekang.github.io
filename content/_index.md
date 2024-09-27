---
# 홈페이지 제목을 사이트 제목으로 사용하려면 비워두세요
title: ""
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: presentation.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Lab's Interests</span>
      text: 저희 연구실에서는 다음과 같은 연구/개발 분야에 관심을 쏟고 있습니다.<br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">의료 (Medical), 항공우주 (Aerospace), 컨텐츠 (Contents) 등 다양한 특성화 분야에 적응형 AI 기술 적용.</span><br><br>
        - name: 멀티모달(Multi-modality)
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">Vision & Language 분야의 기반 AI 기술 개발 및 관련 응용 어플리케이션에 기술 적용.</span><br><br>
        - name: 의료수학(Medical Math)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">의료 분야에 대한 통계 분석 수행 및 의료 질병에 대한 수학적인 모델링 관련 연구 수행.</span><br><br>
        - name: 컨텐츠 (Contents)
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">웹툰 및 미디어 컨텐츠와 관련된 AI 기반 기술 개발 및 고도화.</span><br><br>
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Full-Stack 기반의 응용 어플리케이션 개발.</span><br><br>
        - name: 솔루션 (Solution)
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">AI 기반기술 및 관련 어플리케이션에 적용을 통한 통합 솔루션 개발!</span><br><br>


    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: markdown
    content:
      title: '📚 나에 대해'
      subtitle: ''
      text: |-
        저는 현재 컴퓨터 공학을 전공하며, 웹과 앱 개발, 그리고 인공지능 기술에 관심을 가지고 연구하고 있습니다. 

        2022년 전북대학교에서 컴퓨터공학으로 전과한 이후, 다양한 해커톤과 공모전에 참여하여 많은 성과를 이뤘습니다. 
        2023년 아이디어 해커톤과 지속가능발전목표(SDGs) 프레젠테이션 대회에서 우수상을 수상했고, 2024년 창업 아이디어 메이커톤에서 베스트 피칭상을 수상한 경력이 있습니다.

        저의 목표는 기술을 통해 사회에 긍정적인 변화를 가져오는 것입니다. 또한, 미래에는 인공지능 기술을 활용한 혁신적인 솔루션을 개발하여 의료문제를 해결하는 데 기여하고자 합니다.

        저의 목표 대학원은 서울대입니다.

    design:
      # 레이아웃 보기 선택
      view: date-title-summary
      # 간격 줄이기
      spacing:
        padding: [100px, 0, 0, 0]  # 상단에 100px 간격 추가




  - block: cta-card
    demo: true # Hugo Blox Builder 데모 사이트에서만 이 섹션을 표시
    content:
      title: 👉 이와 같은 학술 웹사이트를 만들어 보세요
      text: |-
        이 사이트는 250,000명 이상의 학자들이 신뢰하는 무료 Hugo 기반 오픈소스 웹사이트 빌더인 Hugo Blox Builder로 생성되었습니다.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="GitHub에서 HugoBlox/hugo-blox-builder에 Star를 주기">Star</a>

        블록으로 쉽게 구축하세요 - 코딩 필요 없음!
        
        랜딩 페이지, 세컨드 브레인, 코스에서 학술 이력서, 컨퍼런스, 기술 블로그까지 모두 구축 가능합니다.
      button:
        text: 시작하기
        url: https://hugoblox.com/templates/
    design:
      card:
        # 카드 배경 색상 (CSS 클래스)
        css_class: "bg-primary-700"
        css_style: ""

# View
view: card

# Optional cover image (relative to `assets/media/` folder).
image:
  caption: ''
  filename: ''
---
