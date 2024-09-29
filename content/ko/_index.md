---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing
sections:



  - block: features
    content:
      title: "<span style=\"font-size:70%\">강경태의 포트폴리오 사이트</span>"
      text: "<br><span style=\"font-size:125%\">강경태의 포트폴리오 사이트에 오신 것을 환영합니다.</span> <br><br>{{% cta cta_link=\"./field/\" cta_text=\"더보기 →\" %}}"

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
          content: <span style="font-size:70%">크몽이나 기타 외주를 받고싶으십니까?</span>
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
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
      interval: 3000

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">강경태의 관심사</span>
      text: 저는 다음과 같은 주제에 관심이 있습니다.<br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: medical
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
      title: 요즘 알아보고 있는 관심사 소개
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





      sections:
  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
      
    design:
      background:
        color: gray

  - block: markdown
    content:
      title: About me
      text: |- 
        <span class="justified-text">
        어릴 때부터 의학, 특히 뇌와 뇌신경에 관심이 많았습니다. 뇌를 연구하기 위해 우선 컴퓨터공학과 인공지능을 배워야겠다는 생각 하에 컴퓨터공학부에 입학했고, 컴퓨터공학부와 바이오메디컬공학부의 수업을 들으며 의학과 의공학, 컴퓨터공학의 전반을 배우고 있습니다. 여러 분야를 넘나들며 연결짓고 융합해 복합적인 무언가를 만들어내는 것을 즐깁니다. 그중에서도 의학과 공학을 융합해 의공학, 뇌공학 전반을 연구하며 뇌를 탐구하고 싶습니다. 의료인공지능의 응용 영역에서도 뇌공학과 뇌신경 쪽, 특히 뇌 컴퓨터 인터페이스 분야의 뇌신경 모델링과 심층신경망 분야에서 뇌의 메커니즘을 해석하는 연구에 관심 있습니다. </span>
        

  - block: features
    content:
      title: "Interests"
      items:
        - name: "인공지능 (AI)"
          icon: code-branch
          icon_pack: fas
        - name: "Data Science"
          icon: database
          icon_pack: fas
        - name: "개발 (Development)"
          icon: laptop
          icon_pack: fas
        - name: "의학, 의공학"
          icon: brain
          icon_pack: fas
        - name: "Medical AI & Brain"
          icon: laptop-medical
          icon_pack: fas
        - name: "Algorithm"
          icon: folder-tree
          icon_pack: fas

    design:
      columns: '1'

  - block: skills
    content:
      title: Languages & Technologies
      text: ''
      username: admin
      css_style: |
        #section-skills > .col-12 {
          display: flex;
          flex-wrap: wrap;
          width: 100%;
          justify-content: flex-start;
        } 
        
        #section-skills .row {
          display: flex;
          flex-direction: column;
        }
        #section-skills .col-12 .col-md-6 {
          flex-direction: column;
          flex: 0 0 25%;
        }
        .skills-content {
          margin-left: 30px;
          margin-right: 30px;
        }
        .skills-wrapper {
          border: 1px solid #00E5E5;
        }
        .skills-percent {
          background-color: #00FFFF;

        }
          
    design:
        columns: '1'

  - block: skills
    content:
      title: Skills
      text: ''
      username: admin2
      css_style: |
        #section-skills > .col-12 {
          display: flex;
          flex-wrap: wrap;
          width: 100%;
          justify-content: flex-start;
        } 
        
        #section-skills .row {
          display: flex;
          flex-direction: column;
        }
        #section-skills .col-12 .col-md-6 {
          display: flex;
          flex: 0 0 50%;
        }
        .skills-content {
          margin-left: 30px;
          margin-right: 30px;
        }
        .skills-wrapper {
          border: 1px solid #00E5E5;
        }
        .skills-percent {
          background-color: #00FFFF;

        }

    design:
      columns: 1

  - block: collection
    content:
      id: section-1
      title: Various Activities
      subtitle:
      text:
      count: 60
      offset: 0
      order: desc
      filters:
        folders:
          - collaborate/Litmus Renewal Project
          - researchproject
          - course/CAPSTONE
    design:
      view: card
      columns: '2'


  - block: features
    content:
      title: Favorites
      items:
        - name: Cat
          icon: cat
          icon_pack: fas
        - name: Book
          icon: book-bookmark
          icon_pack: fas
        - name: Music
          icon: guitar
          icon_pack: fas

        - name: Photography
          icon: camera-retro
          icon_pack: fas
        - name: Coffee & Tea
          icon: mug-saucer
          icon_pack: fas
        - name: Whiskey
          icon: whiskey-glass
          icon_pack: fas

    design:
      columns: 2

  
  - block: experience
    content:
      title: Education
      items:
        - title: M.S. in 전자.정보공학부(컴퓨터공학전공)
          description: 전북대학교 (학석사 연계 과정)
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
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 0
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0

---

<!-- 
---
# 홈페이지 제목을 사이트 제목으로 사용하려면 비워두세요
title: ""

date: 2024-09-20
type: landing

design:
  # 기본 섹션 간격
  spacing: "6rem"


---
# Display name
title: seoharu.github.io

# Name pronunciation (optional)
name_pronunciation: 최서연

# Full name (for SEO)
first_name: SEOYEON
last_name: CHOI

# Status emoji
status:
  icon: 💻

authors:
  - admin
  
# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Student
position: Undergraduate research student

# Organizations/Affiliations to show in About widget
organizations:
  - name: JBNU - Division of Computer Science and Engineering
    url: https://csai.jbnu.ac.kr/csai/index.do
affiliations:
  - name: MACS
    url: https://jbnu.macs.or.kr/
major: 컴퓨터공학
joint_major: 메디컬AI

# Short bio (displayed in user profile at end of posts)
bio: 컴퓨터공학부 학부생이자 메디컬AI 연계전공생입니다. 관련 연구실에서 학부연구생으로 있으면서, 메디컬AI 분야의 연구와 프로젝트를 진행하고 있습니다. 좋아하는 것들로 일상을 채우고 발전하려 끊임없이 노력합니다. 

interests:
  - 인공지능 (AI)
  - 데이터 분석 (Data Science)
  - 개발 (Development)
  - 의학, 의공학
  - Medical AI & Brain
  - Global

education:
  courses:
    - course: M.S. in (전자.정보공학부(컴퓨터공학전공))
      institution: 전북대학교 (학석사 연계 과정)
      year: 2025.09 ~ 2027.02 (예정)
    - course: B.S. in (컴퓨터공학부)
      institution: 전북대학교
      year: 2022 ~ 진행 중 (2025.09 졸업 예정)

skills:
  items:
    - name: 데이터 분석 및 모델링
      description: ''
      percent: 50
      icon: chart-bar
    - name: Front-end
      description: ''
      percent: 40
    - name: Back-end
      description: ''
      percent: 10
    - name: AI
      description: ''
      percent: 30
languages:
  - name: programming
    items: 
      - name: Basic Language
        description: C, C++, Python
      - name: Web-oriented Language
        description: Javascript, TypeScript
  - name: frameworks
    items:
      - name: Deep learning frameworks
        desctription: Python (Tensorflow, pytorch), C++ (CUDA)
      - name: Web frameworks
        description: Vue.js
  - name: DBMS
    items: 
      - name: SQL
        description: MySQL, MongoDB
  - name: AWS
    
  - name: lingual
    items:
      - name: Korean
        description: Native
      - name: English
        description: Academic (studying one semester as exchange students in Malaysia)
      - name: Espanol
        description: daily conversation 

hobbys:
  items:
    - name: 독서
      description: ''
    - name: 악기
      description: 피아노, 바이올린 and 드럼
    - name: 전시회, 공연 감상
    - name: 사진

favorites:
  items:
    - name: Cat
    - name: 


# Social Networking
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:yunseul@jbnu.ac.kr'
    label: E-mail Me
  - icon: github
    url: https://github.com/seoharu
    label: github
  # Link to a PDF of your resume/CV - upload it to `static/uploads/resume.pdf`
  # - icon: academicons/cv
  #   url: uploads/resume.pdf
  #   label: Download my resume
  # - icon: rss
  #   url: ./post/index.xml
  #   label: Subscribe to my blog via RSS feed

# Highlight the author in author lists? (true/false)
highlight_name: true

user_groups:
  - admin

# Author's website URL
website: "https://seoharu.github.io/"
---

어릴 때부터 의학, 특히 뇌와 뇌신경에 관심이 많았습니다. 뇌를 연구하기 위해 우선 컴퓨터공학과 인공지능을 배워야겠다는 생각 하에 컴퓨터공학부에 입학했고, 컴퓨터공학부와 바이오메디컬공학부의 수업을 들으며 의학과 의공학, 컴퓨터공학의 전반을 배우고 있습니다. 여러 분야를 넘나들며 연결짓고 융합해 복합적인 무언가를 만들어내는 것을 즐깁니다. 의학과 공학의 결합으로 의공학, 뇌공학 전반을 연구하는 삶을 살고 싶습니다. 의료인공지능의 응용 영역에서도 뇌공학과 뇌신경 쪽, 특히 뇌 컴퓨터 인터페이스 분야의 뇌신경 모델링과 심층신경망 분야에서 뇌의 메커니즘을 해석하는 연구에 관심 있습니다.


sections:
  - block: features
    content:
      title: Profile
      # 표시할 사용자 프로필 선택 (`content/authors/` 내 폴더명)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: white

        image:
          # `assets/media/`에 배경 이미지를 추가하세요.
          # filename: a.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false


  
        

    design:
      # 레이아웃 보기 선택
      view: date-title-summary
      # 간격 줄이기
      spacing:
        padding: [0, 0, 0, 0]

  - block: collection
    content:
      id: section-1
      title: hobbies
      filters:
        folders:
          - name: 독서
            description: ""
          - name: 악기
            description: 피아노, 바이올린, 그리고 드럼
          - name: 전시회, 공연 감상
            descriptipn: ""
          - name: 사진
            description: 바다, 하늘 등 풍경 사진 찍기 
  - block: collection
    content:
      id: section-2
      title: hobbies
      filters:
        folders:
          - name: "Cat"
            description: ""

  # - block: cta-card
  #   demo: true # Hugo Blox Builder 데모 사이트에서만 이 섹션을 표시
  #   content:
  #     title: "👉 이와 같은 학술 웹사이트를 만들어 보세요"
  #     text: |-
  #       이 사이트는 250,000명 이상의 학자들이 신뢰하는 무료 Hugo 기반 오픈소스 웹사이트 빌더인 Hugo Blox Builder로 생성되었습니다.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="GitHub에서 HugoBlox/hugo-blox-builder에 Star를 주기">Star</a>

  #       블록으로 쉽게 구축하세요 - 코딩 필요 없음!

  #       랜딩 페이지, 세컨드 브레인, 코스에서 학술 이력서, 컨퍼런스, 기술 블로그까지 모두 구축 가능합니다.
  #     button:
  #       text: "시작하기"
  #       url: "https://hugoblox.com/templates/"
    design:
      card:
        # 카드 배경 색상 (CSS 클래스)
        css_class: "bg-primary-700"
        css_style: ""
---