---
title: The Group
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: The Group
      subtitle:
      text: |
        <!-- Team photo will be displayed here -->
    design:
      columns: '1'

  - block: people
    content:
      title:
      user_groups:
        - Postdoctoral Researchers
        - Ph.D. Students
      sort_by: Params.weight
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: false
      show_organizations: false

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
