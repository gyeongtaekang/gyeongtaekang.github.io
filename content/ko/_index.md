---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

- block: layout
  content:
    # Define a 2-column layout for image and text side by side
    columns:
      - width: 50%
        content:
          - block: image
            content:
              title: ""
              text: |
                <img src="media/Ai.jpg" alt="Description of Image" style="max-width: 100%; border-radius: 10px;">
      - width: 50%
        content:
          - block: markdown
            content:
              title: ""
              subtitle: ""
              text: |
                <span style="font-size:125%">여기에 원하는 글을 작성하세요.</span> <br><br>
                텍스트 내용을 이 부분에 추가하세요.
  design:
    # Customize the layout of the columns
    gutter: "20px" # Adjust space between image and text


sections:

  - block: features
    content:
      title: "<span style=\"font-size:70%\">강경태의 포트폴리오 사이트</span>"
      text: "<br><span style=\"font-size:125%\">강경태의 포트폴리오 사이트에 오신 것을 환영합니다.</span> <br><br>{{% cta cta_link=\"./field/\" cta_text=\"더보기 →\" %}}"

  - block: image
    id: profile-image
    content:
      title: ""
      text: |
        <!-- Add the image below -->
        <img src="media/me.jpg" alt="My Image" style="max-width: 300px; border-radius: 10px;">



  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">공모전</span>
        content: <span style="font-size:70%">다양한 공모전에 관심있으십니까?</span>
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

      - title: <span style="font-size:70%">아웃소싱(외주)</span>
        content: <span style="font-size:70%">크몽이나 기타 외주를 받고싶으십니까?<span style="font-size:70%">
        align: center
        background:
          image:
            filename: Ai.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">코딩</span>
        content: <span style="font-size:70%">컴퓨터 과학이나 코딩에 관심있으십니까?</span>
        align: center
        background:
          image:
            filename: healthcare.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">런닝</span>
        content: <span style="font-size:70%">매일 10km씩 뛰면서 다이어트 하고싶으세요?</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">대학원</span>
        content: <span style="font-size:70%">학부 공부를 넘어서 대학원진학에 관심있으세요?</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: features
    id: features
    content:
      title: <span style="font-size:75%">강경태의 관심사</span>
      text: 저는 다음과 같은 주제에 관심이 있습니다.<br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: medical.svg
          icon_pack: fas
          description: <span style="font-size:90%">기계학습,딥러닝,Rnn,컴퓨터 비전 등등</span><br><br>
        - name: 런닝
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">하루에 10km씩 런닝하면서 체중감소</span><br><br>
        - name: 노래
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">꾀꼬리 같은 맑은 보이스를 가진 혼코노러버</span><br><br>
        - name: 의료
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">의료지식을 공부하며 어떻게 의료인공지능과 결합할지 고민</span><br><br>
        - name: 주식
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">미장위주, 금리인하,실적발표,Rsi등등 투자와 돈불리는것에 관심</span><br><br>
        - name: 전자기기
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">노트북,스마트폰등 혼자서 분해 조립가능</span><br><br>


  - block: collection
    content:
      id: section-1
      title: Notifications & News
      subtitle:
      text:
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
      title: Latest Publications
      subtitle:
      text:
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Join team →" %}}
    design:
      columns: '1'
---