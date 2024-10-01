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
        안녕하세요! 저는 전북대학교 컴퓨터공학부 학생으로, 인공지능(AI)과 데이터 분석에 관심이 많습니다. 원래 의류학을 전공하다가 새로운 도전을 위해 컴퓨터공학으로 전과하였고, 그 이후 다양한 프로젝트와 공모전에 참여하며 성장해 왔습니다. 현재는 의료 AI 분야에서 활발하게 활동하며 기술과 혁신을 통해 사회에 긍정적인 변화를 가져오고자 노력하고 있습니다. 끊임없이 배우고 도전하며, 주어진 모든 기회를 통해 더 나은 세상을 만들어가는 것이 저의 목표입니다.
        </span>

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
      view: compact
      columns: '2'

  - block: collection
    content:
      id: section-1
      title: 내 프로젝트
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - field
    design:
      view: list
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
        - title: 이공계열
          description: 전주고등학교
          date_start: '2016-03-02'
          date_end: '2019-12-31'
        - title: B.S. in (컴퓨터공학부)
          description: 전북대학교 (JBNU) 컴퓨터공학부
          date_start: '2020-03-02'
          date_end: '2025-08-31'

  - block: tag_cloud
    content:
      title: My tags
      subtitle: ''
      text: 사용한 태그들
      taxonomy: tags
      count: 0
    design:
      font_size_min: 0.7
      font_size_max: 2.0
---
