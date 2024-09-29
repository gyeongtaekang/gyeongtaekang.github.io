---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing
sections:


  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
    design:
      background:
        image:
          filename: 18216.jpg
          # Optional: Set background image options
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: About me
      text: |- 
        <span class="justified-text" style="color: gray;">
        어릴 때부터 의학, 특히 뇌와 뇌신경에 관심이 많았습니다. 뇌를 연구하기 위해 컴퓨터공학과 인공지능을 배워야겠다는 생각 하에 컴퓨터공학부에 입학했고, 컴퓨터공학부와 바이오메디컬공학부의 수업을 들으며 의학과 의공학, 컴퓨터공학의 전반을 배우고 있습니다. 여러 분야를 넘나들며 융합하고 탐구하는 것을 즐깁니다. 의료 인공지능과 뇌공학 분야에서 뇌의 메커니즘을 해석하는 연구에 관심이 있습니다.
        </span>

  - block: features
    content:
      title: "Interests"
      items:
        - name: "인공지능 (AI)"
          icon: brain
          icon_pack: fas
        - name: "Data Science"
          icon: database
          icon_pack: fas
        - name: "개발 (Development)"
          icon: laptop
          icon_pack: fas
        - name: "의학, 의공학"
          icon: hospital
          icon_pack: fas
        - name: "Medical AI & Brain"
          icon: laptop-medical
          icon_pack: fas
        - name: "Algorithm"
          icon: code
          icon_pack: fas

    design:
      columns: '1'


  - block: features
    content:
      title: "<span style=\"font-size:70%\">강경태의 포트폴리오 사이트</span>"
      text: "<br><span style=\"font-size:125%\">강경태의 포트폴리오 사이트에 오신 것을 환영합니다.</span> <br><br>{{% cta cta_link=\"./field/\" cta_text=\"더보기 →\" %}}"

  - block: slider
    content:
      slides:
        - title: "<span style=\"font-size:70%\">공모전</span>"
          content: "<span style=\"font-size:70%\">다양한 공모전에 관심있으십니까?</span>"
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
            text: "<span style=\"font-size:60%\">Join Us</span>"
            text-color: '#000'
            url: contact

        - title: "<span style=\"font-size:70%\">아웃소싱(외주)</span>"
          content: "<span style=\"font-size:70%\">크몽이나 기타 외주를 받고싶으십니까?</span>"
          align: center
          background:
            image:
              filename: Ai.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: "<span style=\"font-size:70%\">코딩</span>"
          content: "<span style=\"font-size:70%\">컴퓨터 과학이나 코딩에 관심있으십니까?</span>"
          align: center
          background:
            image:
              filename: healthcare.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: "<span style=\"font-size:70%\">런닝</span>"
          content: "<span style=\"font-size:70%\">매일 10km씩 뛰면서 다이어트 하고싶으세요?</span>"
          align: center
          background:
            image:
              filename: mathematics.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: "<span style=\"font-size:70%\">대학원</span>"
          content: "<span style=\"font-size:70%\">학부 공부를 넘어서 대학원진학에 관심있으세요?</span>"
          align: center
          background:
            image:
              filename: development.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

    design:
      slide_height: '350px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000

  - block: features
    id: features
    content:
      title: "<span style=\"font-size:75%\">강경태의 관심사</span>"
      text: "저는 다음과 같은 주제에 관심이 있습니다.<br><br>"
      items:
        - name: 인공지능(AI)
          icon: brain
          icon_pack: fas
          description: "<span style=\"font-size:90%\">기계학습, 딥러닝, RNN, 컴퓨터 비전 등등</span>"
        - name: 런닝
          icon: running
          icon_pack: fas
          description: "<span style=\"font-size:90%\">하루에 10km씩 런닝하며 체중감소</span>"
        - name: 노래
          icon: music
          icon_pack: fas
          description: "<span style=\"font-size:90%\">맑은 보이스의 혼코노러버</span>"
        - name: 의료
          icon: hospital
          icon_pack: fas
          description: "<span style=\"font-size:90%\">의료지식을 공부하며 의료 인공지능과의 결합 고민</span>"
        - name: 주식
          icon: chart-line
          icon_pack: fas
          description: "<span style=\"font-size:90%\">미장위주, 금리인하, 실적발표, RSI 등 투자와 재테크에 관심</span>"
        - name: 전자기기
          icon: mobile-alt
          icon_pack: fas
          description: "<span style=\"font-size:90%\">노트북, 스마트폰 등의 분해 및 조립 가능</span>"

  - block: collection
    content:
      id: section-1
      title: Notifications & News
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '2'

  - block: collection
    content:
      title: 요즘 알아보고 있는 관심사 소개
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"




  - block: experience
    content:
      title: Education
      items:
        - title: M.S. in 전자.정보공학부(컴퓨터공학전공)
          description: 전북대학교 
          date_start: '2025-09-02'
          date_end: '2027-02-28'
        - title: B.S. in (컴퓨터공학부)
          description: 전북대학교 (JBNU) 컴퓨터공학부
          date_start: '2022-03-02'
          date_end: '2025-08-31'

  - block: tag_cloud
    content:
      title: My tags
      subtitle: ''
      text: 어떤 태그들을 주로 사용했는지 확인할 수 있습니다.
      taxonomy: tags
      count: 0
    design:
      font_size_min: 0.7
      font_size_max: 2.0
---
