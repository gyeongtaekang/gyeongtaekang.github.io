---
title: People
date: 2024-06-11

type: landing

sections:
  - block: people
    content:
      title: 주인
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - human
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: people
    content:
      title: 애완동물
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - pet
          # - 박사과정
          # - 석사과정
          # - 학부연구생
          # - Principal Investigators
          # - Researchers
          # - Grad Students
          # - Administration
          # - Visitors
          # - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: false
      show_social: false
      columns: 2
---