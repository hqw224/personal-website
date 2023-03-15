---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: collection
    id: Research
    content:
      title: Research Papers
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    id: teaching
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2021-01-01'
          date_start: '2021-04-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: NCCT5020 Microeconomics for Management (Prof. Robert Frank)
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2021-03-01'
          date_start: '2021-05-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: NBA6950 Game Theory and Business Strategy (Prof. Yi Chen)
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2021-01-01'
          date_start: '2021-04-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: NCC5020 Microeconomics for Management (Prof. Yi Chen)
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2019-05-01'
          date_start: '2019-06-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: NCC5220 Microeconomics for Management (Prof. Yi Chen)
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2020-05-01'
          date_start: '2020-07-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: NCC5020 Microeconomics for Management (Prof. Yi Chen)
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2020-03-01'
          date_start: '2020-05-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: NBA6950 Game Theory and Business Strategy (Prof. Yi Chen)
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2019-08-01'
          date_start: '2019-10-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: NCC5020 Microeconomics for Management (Prof. Michael Waldman)
          url: ''

    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Education'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2024-05-01'
          date_start: '2018-01-25'
          description: ''
          organization: Cornell University
          #organization_url: https://www.coursera.org
          title: Ph.D. in Economics
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2018-06-01'
          date_start: '2015-08-31'
          description: ''
          organization: Fudan University
          #organization_url: https://www.coursera.org
          title: Master's Program in Economics
          url: ''
        - #certificate_url: 'https://www.coursera.org'
          date_end: '2015-06-01'
          date_start: '2011-08-31'
          description: ''
          organization: Zhejiang University
          #organization_url: https://www.coursera.org
          title: BA in Economics
          url: ''
    design:
      columns: '2'
  - block: collection
    id: others
    content:
      title: Miscellaneous
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'

---
