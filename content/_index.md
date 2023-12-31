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
        - title: Visting Researcher
          company: SimTech - Cluster of Excellence
          company_url: 'https://www.simtech.uni-stuttgart.de/'
          company_logo: logo_simtech
          location: University of Stuttgart, Germany
          date_start: '2023-10-01'
          date_end: '2023-11-01'
          description: Development of a reduced-order modeling with uncertainty quantification framework using generative AI algorithms.
        - title: Research Intern
          company: Artificial Intelligence Institute in Dynamic Systems
          company_url: 'https://dynamicsai.org/'
          company_logo: AI_logo
          location: University of Washington, Seattle (US)
          date_start: '2022-10-01'
          date_end: '2023-06-01'
          description: Development of machine learning algorithms for dimensionality reduction and system identification in complex, high-dimensional scenarios in engineering sciences.
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
          description: One year exchange program to study and work on projects related to bayesian statistics, high performance computing and discrete/continuum optimization.
        - title: Professional Athlete
          company: International Gymnastics Federation
          company_url: ''
          company_logo: FIG
          location: Bergamo, Italy
          date_start: '2010-01-01'
          date_end: '2021-12-31'
          description: Member of the National Team of Aerobic Gymnastics. World and European medallist.
            Experiences in coaching and coreographing in Italy, France, Finland, Hungary and Lithuania.
            
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
        - name: Other
          tag: Demo
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
      email: paolo.conti@polimi.it
      phone:  
      # appointment_url: 'https://calendly.com'
      address:
        street: P.zza Leonardo Da Vinci, 32
        city: Milano
        region: MI
        postcode: '20133'
        country: Italy
      directions:  Department of Civil and Environmental Engineering. Building 4
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
