---
# Leave the homepage title empty to use the site title
title: Paolo Conti
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title:
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
        - title: Research Associate
          company: The Alan Turing Institute
          company_url: 'https://www.turing.ac.uk/research/research-programmes/fundamental-ai'
          company_logo: logo_Alan
          location: London, UK
          date_start: '2025-03-03'
          date_end: ''
          description:  |
            Research Associate in Fundamental Research in AI for physical systems, with the aim of developing the next generation of foundational methods, tools and theory to enable modelling, prediction and control of physical systems. 
        - title: Visting Researcher
          company: Imperial College London
          company_url: 'https://www.imperial.ac.uk/'
          company_logo: logo_ICL
          location: London, UK
          date_start: '2023-12-01'
          date_end: '2024-01-01'
          description:  |
            Led a research project to develop generative AI/ML frameworks for data-driven, reduced-order modeling under uncertainty.
            - Conceptualized and implemented a data-driven framework based on variational reduced-order modeling with variational dynamics identification for scientific discovery in the presence of model and measurement uncertainties.
      
        - title: Visting Researcher
          company: SimTech - Cluster of Excellence
          company_url: 'https://www.simtech.uni-stuttgart.de/'
          company_logo: logo_simtech
          location: University of Stuttgart, Germany
          date_start: '2023-10-01'
          date_end: '2023-11-01'
          description: |
            Developed the Python package VINDy to perform data-driven modeling of dynamical systems with generative AI.
 
        - title: Visiting Research Scientist
          company: Artificial Intelligence Institute in Dynamic Systems
          company_url: 'https://dynamicsai.org/'
          company_logo: AI_logo
          location: University of Washington, Seattle (US)
          date_start: '2022-10-01'
          date_end: '2023-06-01'
          description:  |
            Developed ML algorithms for dimensionality reduction and system identification in complex, high-dimensional scenarios in engineering sciences.
            - Designed and constructed physics-informed models for Micro-Electrical Mechanical Systems (MEMS) devices. Application and validation on MEMS micromirrors and resonator devices.
            - Developed a multi-fidelity method to recover and predict high-quality solutions from multi-modal, low-fidelity data sources.
    
     #     description: |2-
     #         Responsibilities include:
     #
     #              * Analysing
     #        * Modelling
     #        * Deploying
        - title: Exchange program
          company: Applied Mathematics, Sorbonne University
          company_url: 'https://www.sorbonne-universite.fr/en'
          company_logo: Sorbonne
          location: Paris, France
          date_start: '2019-09-01'
          date_end: '2020-07-01'
          description: Study abroad coursework in the departments of Applied Mathematics and Sorbonne Polytech.
        - title: Professional Athlete
          company: International Gymnastics Federation
          company_url: ''
          company_logo: FIG
          location: Bergamo, Italy
          date_start: '2010-01-01'
          date_end: '2021-12-31'
          description: |
              - Member of the National Team of Aerobic Gymnastics from 2010 to 2021.
              - World medallist and European champion.
              - Experiences in coaching and coreographing in Italy, France, Finland, Hungary, Lithuania and United States.
            
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Applied Statistics
          tag: Applied Statistics
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    id: gymnastics
    content:
      title: Gymnastics
      filters:
        folders:
          - gymnastics
    design:
      columns: '2'
      view: compact
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
 # - block: tag_cloud
 #   content:
 #     title: Popular Topics
 #   design:
 #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: pconti@turing.ac.uk
      phone:  
      # appointment_url: 'https://calendly.com'
      address:
        street: British Library, 96 Euston Rd.
        city: London
        region: 
        postcode: 'NW1 2DB'
        country: UK
      directions:  The Alan Turing Institute
      contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
        - icon: linkedin
          icon_pack: fab
          name: Connect on
          link: 'https://linkedin.com/in/paolo--conti'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---
