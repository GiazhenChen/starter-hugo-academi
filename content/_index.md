---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research assistant
          company: State Key Laboratory of Tribology in Advanced Equipment
          company_url: ''
          company_logo: thu
          location: Beijing
          date_start: '2023-02-20'
          date_end: ''
          description: |2-
              Responsibilities include:I am currently involved in a project titled 'Mechanisms in transfer film evolution of PTFE coating on mating surface texturing.' This project aims to investigate the transfer film evolution mechanisms of polytetrafluoroethylene (PTFE) coating on textured mating surfaces. The transfer film is a thin layer that transfers from the coating surface to the mating surface and plays a crucial role in reducing friction and wear. By gaining a deeper understanding of the interactions and influencing factors between PTFE coatings and textured mating surfaces, our research aims to reveal the mechanisms and behavior of transfer film evolution. We employ experimental methods, combining microscopic observations, material characterization techniques, surface analysis, and friction-wear testing, to study the effects of different texture features on transfer film formation and performance. Through this research, we hope to provide new insights and solutions for improving coating technologies and enhancing the wear resistance and lubrication performance of mating surfaces.
              * tribological testing
              * mechanism analysis
              * data processing
        - title: Research assistant
          company: National Engineering Research Center for Water Transport Safety
          company_url: ''
          company_logo: whut
          location: Wuhan
          date_start: '2020-09-01'
          date_end: '2023-06-30'
          description: I have focused my research on studying methods to enhance the performance of ship water-lubricated bearings. Specifically, I have investigated various approaches aimed at improving the lubrication efficiency, reducing frictional losses, and enhancing the overall durability and reliability of these bearings in marine environments. My research has involved experimental investigations, numerical modeling, and analysis of the effects of different factors such as bearing design, material selection, water properties, and operating conditions. Additionally, I have explored the utilization of advanced technologies, such as surface modifications and additives, to optimize the performance of water-lubricated bearings. Through my work, I aim to contribute to the development of more efficient and environmentally-friendly bearing systems for marine applications.In addition, I have also been involved in the development of a high-temperature and high-pressure cylinder liner piston ring test rig, where I was responsible for designing the sealing components and some parts of the power system.
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
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
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Water-lubricated bearings
          tag: Water-lubricated bearings
        - name: PTFE transfer film 
          tag: PTFE transfer film 
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: jiazhenchen2@ucmerced.edu
      address:
        street: 5200 Lake Rd
        city: Merced, California 95343
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
