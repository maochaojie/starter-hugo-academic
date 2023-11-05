---
# Leave the homepage title empty to use the site title
title: 'Profile of Chaojie Mao'
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: My Profile
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      #   Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      # date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Alibaba Algorithm Expert
          company: Alibaba Group
          company_url: ''
          company_logo: org-gc
          location: Hangzhou
          date_start: '2018-04-02'
          date_end: ''
          description: |2-
              Responsibilities include:
              * From 2022.6 ~ current: R & D in Image Generation and Foundational Model Tuning.
              * From 2019.4 ~ 2022.6: R & D in MultiMedia AI Application on video understanding.
              * From 2018.4 ~ 2019.4: The algorithm research in image based goods recognition.
        - title: Postgraduate student
          company: Zhejiang University
          company_url: ''
          company_logo: org-x
          location: Hangzhou
          date_start: '2015-06-30'
          date_end: '2018-03-30'
          description: Research on person reid.
    design:
      columns: '2'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Recent work
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  - block: collection
    id: posts
    content:
      title: Recent Work
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
  
  - block: collection
    id: featured
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 4
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  #- block: contact
  #  id: contact
  #  content:
  #    title: Contact
  #    subtitle:
  #    text: |-
  #      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #    # Contact (add or remove contact options as necessary)
  #    email: test@example.org
  #    phone: 888 888 88 88
  #    appointment_url: 'https://calendly.com'
  #    address:
  #      street: 450 Serra Mall
  #      city: Stanford
  #      region: CA
  #      postcode: '94305'
  #      country: United States
  #      country_code: US
  #    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #    office_hours:
  #      - 'Monday 10:00 to 13:00'
  #      - 'Wednesday 09:00 to 10:00'
  #    contact_links:
  #      - icon: twitter
  #        icon_pack: fab
  #        name: DM Me
  #        link: 'https://twitter.com/Twitter'
  #      - icon: skype
  #        icon_pack: fab
  #        name: Skype Me
  #        link: 'skype:echo123?call'
  #      - icon: video
  #        icon_pack: fas
  #        name: Zoom Me
  #        link: 'https://zoom.com'
  #    # Automatically link email and phone or display as text?
  #    autolink: true
  #    # Email form provider
  #    form:
  #      provider: netlify
  #      formspree:
  #        id:
  #      netlify:
  #        # Enable CAPTCHA challenge to reduce spam?
  #        captcha: false
  #  design:
  #    columns: '2'
---
