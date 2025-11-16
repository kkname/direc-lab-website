---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: DiReC Lab
      subtitle: Digital Innovation and Research in Construction
      text: |
        <br>

        We advance data-driven and AI-enabled approaches to improve work processes, efficiency, and sustainability across the built environment.

        <br>
  
  - block: markdown
    content:
      title: Research
      subtitle:
      text: |
        Our research focuses on four key areas:

        **Project Intelligence** — Automating interpretation of project documents and generating solutions through AI and data analytics

        **Data Interoperability** — Creating open, standards-based models for systems compatibility in asset-intensive industries

        **Workforce Solutions** — Addressing construction labor shortages through productivity improvements and development strategies

        **Educational Innovation** — Employing interactive games and simulations to enhance project management training effectiveness

        [View Research →](./research/)
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: compact
      columns: '1'

  - block: collection
    content:
      title: News
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
      page_type: post
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
