---
# Leave the homepage title empty to use the site title
title: Main Page
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
      title: About Me
      text: |- 
        <span class="justified-text" style="color: gray;text-align: justify;">
        Hello! I am a student at Chonbuk National University majoring in Computer Science, with a strong interest in Artificial Intelligence (AI) and Data Analysis. I originally majored in Clothing but switched to Computer Science for a new challenge. Since then, I have participated in various projects and contests, continually growing. Currently, I am active in the field of medical AI, striving to bring positive change to society through technology and innovation. My goal is to continue learning, challenging myself, and eventually join the AI research lab at Seoul National University.
        </span>

  - block: features
    id: features
    content:
      title: "<span style=\"font-size:75%\">Gyeongtae Kang's Interests</span>"
      text: "I am interested in the following topics:<br><br>"
      items:
        - name: Artificial Intelligence (AI)
          icon: brain
          icon_pack: fas
          description: "<span style=\"font-size:90%\">Machine Learning, Deep Learning, RNN, FCN, Computer Vision, etc.</span>"
        - name: Running
          icon: running
          icon_pack: fas
          description: "<span style=\"font-size:90%\">Running 10km every day for weight loss</span>"
        - name: Music
          icon: music
          icon_pack: fas
          description: "<span style=\"font-size:90%\">Owner of a clear and beautiful voice, a karaoke lover</span>"
        - name: Medicine
          icon: hospital
          icon_pack: fas
          description: "<span style=\"font-size:90%\">Studying medical knowledge and exploring its combination with AI</span>"
        - name: Stocks
          icon: chart-line
          icon_pack: fas
          description: "<span style=\"font-size:90%\">Focused on U.S. stocks, interested in interest rate cuts, earnings reports, RSI, etc.</span>"
        - name: Electronics
          icon: mobile-alt
          icon_pack: fas
          description: "<span style=\"font-size:90%\">Able to disassemble and assemble laptops, smartphones, and other devices</span>"

  - block: features
    content:
      title: "<span style=\"font-size:70%\">Gyeongtae Kang's Portfolio Site</span>"
      text: "<br><span style=\"font-size:125%\">Welcome to Gyeongtae Kang's portfolio site.</span> <br><br>{{% cta cta_link=\"./field/\" cta_text=\"See More →\" %}}"

  - block: slider
    content:
      slides:
        - title: "<span style=\"font-size:70%\">Competitions</span>"
          content: "<span style=\"font-size:70%\">Are you interested in various competitions?</span>"
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
            text: "Image Source: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/photos/GraajutbJHE"

        - title: "<span style=\"font-size:70%\">Outsourcing</span>"
          content: "<span style=\"font-size:70%\">Interested in outsourcing on platforms like Kmong?</span>"
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
            text: "Image Source: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/photos/1Z2niiBPg5A"

        - title: "<span style=\"font-size:70%\">Coding</span>"
          content: "<span style=\"font-size:70%\">Are you interested in computer science or coding?</span>"
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
            text: "Image Source: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/photos/1OtUkD_8svc"

        - title: "<span style=\"font-size:70%\">Running</span>"
          content: "<span style=\"font-size:70%\">Would you like to run 10km daily for weight loss?</span>"
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
            text: "Image Source: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/photos/Apj4nSemkzk"

        - title: "<span style=\"font-size:70%\">Graduate Studies</span>"
          content: "<span style=\"font-size:70%\">Are you interested in pursuing studies beyond your undergraduate degree?</span>"
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
            text: "Image Source: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/photos/s9CC2SKySJM"

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
      title: My Projects
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
      title: Introducing My Interests
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
        - title: Science and Engineering Track
          description: Jeonju High School
          date_start: '2016-03-02'
          date_end: '2019-12-31'
        - title: B.S. in Computer Science
          description: Chonbuk National University (JBNU), Department of Computer Science
          date_start: '2020-03-02'
          date_end: '2025-08-31'

  - block: tag_cloud
    content:
      title: My Tags
      subtitle: ''
      text: Tags Used
      taxonomy: tags
      count: 0
    design:
      font_size_min: 0.7
      font_size_max: 2.0
---
