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
      title: '📚 나의 연구'
      subtitle: ''
      text: |-
        저는 의료 인공지능와 만화 인공지능을 연구하고있습니다. 또한 웹과 앱 개발을 하고있습니다.
        
        2023년 12월 제1회 아이디어 해커톤에서 최우수상 경력과 2023년부터 2024년까지 7개의 글쓰기 공모전에서 수상한 경력도 있습니다.

        저의 목표 대학원은 서울대입니다



    design:
      # 레이아웃 보기 선택
      view: date-title-summary
      # 간격 줄이기
      spacing:
        padding: [0, 0, 0, 0]
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
