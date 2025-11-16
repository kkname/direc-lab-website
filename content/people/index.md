---
title: People
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: People
      subtitle:
      text:
    design:
      columns: '1'

  - block: people
    content:
      title: Director
      user_groups:
          - Director
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: people
    content:
      title: Postdoctoral Researchers
      user_groups:
          - Postdoctoral Researchers
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: people
    content:
      title: Ph.D. Students
      user_groups:
          - Ph.D. Students
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: people
    content:
      title: Master's Students
      user_groups:
          - Master's Students
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: people
    content:
      title: Visiting Scholars
      user_groups:
          - Visiting Scholars
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: people
    content:
      title: Alumni
      user_groups:
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: false
---