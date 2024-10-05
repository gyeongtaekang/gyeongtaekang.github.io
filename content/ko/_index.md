---
# Leave the homepage title empty to use the site title
title: 메인페이지
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
        <span class="justified-text" style="color: gray;text-align: justify;">
        안녕하세요! 저는 전북대학교 컴퓨터공학부 학생으로, 인공지능(AI)과 데이터 분석에 관심이 많습니다. 원래 의류학을 전공하다가 새로운 도전을 위해 컴퓨터공학으로 전과하였고, 그 이후 다양한 프로젝트와 공모전에 참여하며 성장해 왔습니다. 현재는 의료 AI 분야에서 활발하게 활동하며 기술과 혁신을 통해 사회에 긍정적인 변화를 가져오고자 노력하고 있습니다. 끊임없이 배우고 도전하며, 서울대 의료인공지능 연구실로 진학하는것이 저의 목표입니다.
        </span>

- block: features
  id: features
  content:
    title: "<span style=\"font-size:75%\">강경태의 관심사🧐</span>"
    text: "저는 다음과 같은 주제에 관심이 있습니다✍️<br><br>"
    items:
      - name: 인공지능(AI)
        icon: robot
        icon_pack: fas
        icon_color: "#FF0000" # 빨간색
        description: "<span style=\"font-size:90%\">🤖 기계학습, 딥러닝, RNN, FCN, 컴퓨터 비전 등 다양한 분야의 인공지능에 관심이 있습니다.</span>"
      - name: 런닝
        icon: running
        icon_pack: fas
        icon_color: "#FFA500" # 주황색
        description: "<span style=\"font-size:90%\">🏃‍♂️ 하루에 10km씩 런닝하며 체중감소와 체력 증진을 추구합니다.</span>"
      - name: 노래
        icon: microphone
        icon_pack: fas
        icon_color: "#FFFF00" # 노란색
        description: "<span style=\"font-size:90%\">🎤 꾀꼬리 같은 맑은 보이스를 가진 혼코노러버! 노래 부르는 것이 저의 힐링입니다.</span>"
      - name: 인생을 더 잘사는법
        icon: lightbulb
        icon_pack: fas
        icon_color: "#008000" # 초록색
        description: "<span style=\"font-size:90%\">💡 남들보다 앞서가는 인생을 살기 위해 고민하고 실천 중입니다. 자기개발과 성장에 항상 초점을 맞추고 있어요.</span>"
      - name: 재테크
        icon: dollar-sign
        icon_pack: fas
        icon_color: "#0000FF" # 파란색
        description: "<span style=\"font-size:90%\">💹 복리효과를 누리기 위해 젊을 때 적극적으로 도전하고 있습니다. 현재는 대기업 위주의 장기투자에 집중하며, 신중한 전략을 추구합니다.</span>"
      - name: 책
        icon: book
        icon_pack: fas
        icon_color: "#4B0082" # 남색
        description: "<span style=\"font-size:90%\">📚 상상력을 키우는 소설보다는, 관심 분야에 대한 지식을 키우기 위한 실용서적을 즐겨 읽습니다. 특히 재테크 관련 책도 5권 이상 읽었습니다.</span>"





  - block: features
    content:
      title: "<span style=\"font-size:70%\">강경태의 포트폴리오 사이트</span>"
      text: "<br><span style=\"font-size:125%\">버튼 hover 색변화</span> <br><br>{{% cta cta_link=\"./field/\" cta_text=\"더보기 →\" %}}"

- block: features
  content:
    title: "<span style=\"font-size:70%\">강경태의 포트폴리오 사이트</span>"
    text: "<br><span style=\"font-size:125%\">버튼 hover 색변화</span> <br><br>{{% cta cta_link=\"./field/\" cta_text=\"더보기 →\" %}}"

  - block: slider
    content:
      slides:
        - title: "<span style=\"font-size:70%\">공모전</span>"
          content: "<span style=\"font-size:70%\">다양한 공모전에 관심있으십니까?</span>"
          align: center
          background:
            image:
              filename: forest.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%88%B2-%EC%86%8D-%EC%98%A4%EC%86%94%EA%B8%B8-GraajutbJHE"
          # 슬라이더에 버튼 추가
          button: "<button class=\"slider-button\">자세히 보기</button>"

        - title: "<span style=\"font-size:70%\">아웃소싱(외주)</span>"
          content: "<span style=\"font-size:70%\">크몽이나 기타 외주를 받고싶으십니까?</span>"
          align: center
          background:
            image:
              filename: forest1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/foggy-mountain-summit-1Z2niiBPg5A"
          button: "<button class=\"slider-button\">자세히 보기</button>"

        - title: "<span style=\"font-size:70%\">코딩</span>"
          content: "<span style=\"font-size:70%\">컴퓨터 과학이나 코딩에 관심있으십니까?</span>"
          align: center
          background:
            image:
              filename: forest2.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%ED%91%B8%EB%A5%B8-%EB%B3%84%EC%9D%B4-%EB%B9%9B%EB%82%98%EB%8A%94-%EB%B0%A4-1OtUkD_8svc"
          button: "<button class=\"slider-button\">자세히 보기</button>"

        - title: "<span style=\"font-size:70%\">런닝</span>"
          content: "<span style=\"font-size:70%\">매일 10km씩 뛰면서 다이어트 하고싶으세요?</span>"
          align: center
          background:
            image:
              filename: 런닝.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%BD%98%ED%81%AC%EB%A6%AC%ED%8A%B8-%EB%8F%84%EB%A1%9C%EB%A5%BC-%EB%8B%AC%EB%A6%AC%EB%8A%94-%EC%82%AC%EB%9E%8C-Apj4nSemkzk"
          button: "<button class=\"slider-button\">자세히 보기</button>"

        - title: "<span style=\"font-size:70%\">대학원</span>"
          content: "<span style=\"font-size:70%\">학부 공부를 넘어서 대학원진학에 관심있으세요?</span>"
          align: center
          background:
            image:
              filename: 공부.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%ED%9D%B0%EC%83%89-%EC%84%B8%EB%9D%BC%EB%AF%B9-%EB%A8%B8%EA%B7%B8%EC%9E%94-%EA%B7%BC%EC%B2%98%EC%9D%98-%EA%B0%88%EC%83%89-%EB%82%98%EB%AC%B4-%ED%85%8C%EC%9D%B4%EB%B8%94%EC%97%90-%EA%B8%80%EC%9D%84-%EC%93%B0%EB%8A%94-%EC%82%AC%EB%9E%8C-s9CC2SKySJM"
          button: "<button class=\"slider-button\">자세히 보기</button>"

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
      view: community/custom_card
      columns: '2'


  - block: collection
    content:
      title: 관심사 소개
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
