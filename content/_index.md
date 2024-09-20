---
# 홈페이지 제목을 사이트 제목으로 사용하려면 비워두세요
title: ""
date: 2022-10-24
type: landing

design:
  # 기본 섹션 간격
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # 표시할 사용자 프로필 선택 (`content/authors/` 내 폴더명)
      username: admin
      text: ""
      # 전기 아래에 동작 버튼을 표시할까요? (선택 사항)

    design:
      css_class: dark
      background:
        color: black
        image:
          # `assets/media/`에 배경 이미지를 추가하세요.
          filename: a.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
          
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
        padding: [100px, 0, 0, 0]  # 상단에 50px 간격 추가

  - block: resume-experience
    content:
      title: 'Work Experience'
      items:
        - position: 그린컴퓨터 학원
          company_name: 그린아트
          company_url: ''
          company_logo: ''
          date_start: 2022-03-01
          date_end: 2022-05-15
          summary: |
            배운 내용:
            - 웹을 처음 접하기도 했고 프론트 엔드 부분을 배웠습니다.
            - 이 경험은 웹을 독학할 수 있는 기반이 되었습니다.

        - position: 풀스택 소프트웨어 개발자
          company_name: 프리랜서
          company_url: ''
          company_logo: ''
          date_start: 2022-01-01
          date_end: 2022-12-31
          summary: |
            주요 프로젝트:
            - React Native와 Android Studio를 사용하여 모바일 애플리케이션 개발
            - 다양한 API와의 연동을 통해 백엔드 통합 구현
            - 프론트엔드와 백엔드 모두를 아우르는 풀스택 프로젝트 참여
            - 크몽 플랫폼에서 프리랜서로 활동하며 고객 맞춤형 웹 및 앱 솔루션 제공


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
---
