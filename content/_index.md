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
        - title: Científico Titular
          company: CSIC
          company_url: ''
          company_logo: ''
          location: IGEO, Madrid
          date_start: '2024-01-09'
          date_end: ''
          description: |2-
              Geodynamics:

              * Global Tectonics
              * Paleomagnetism
              * Continental Crust
        - title: Ramón y Cajal Fellow
          company: University of Granada
          company_url: ''
          company_logo: ''
          location: Granada
          date_start: '2021-05-01'
          date_end: '2024-01-08'
          description: ''
        - title: Assistant Professor (助教) of Tectonics
          company: Tohoku University
          company_url: ''
          company_logo: ''
          location: Sendai
          date_start: '2019-06-01'
          date_end: ''
          description: ''
        - title: JSPS Fellow
          company: Tohoku University
          company_url: ''
          company_logo: ''
          location: Sendai
          date_start: '2016-09-29'
          date_end: '2018-09-29'
          description: ''
        - title: Postdoctoral Fellow
          company: Utrecht University
          company_url: ''
          company_logo: ''
          location: Utrecht
          date_start: '2013-01-01'
          date_end: '2016-07-31'
          description: ''
    design:
      columns: '2'
#  - block: accomplishments
#    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Awards'
#      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
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
    id: publication
    content:
      title: Recent Publications
      text: |-
        [SEE ALL PUBLICATIONS](./publication/)
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: portfolio
    id: team
    content:
      title: Team
      filters:
        folders:
          - team
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: Present
          tag: 'Present'
        - name: Past
          tag: 'Past'
        - name: MSc
          tag: 'MSc'
        - name: BSc
          tag: 'BSc'         
        - name: PhD
          tag: 'PhD' 
        - name: All
          tag: '*' 
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
     # flip_alt_rows: false
  - block: collection
    id: fieldwork
    content:
      title: Fieldwork
      count: 3
      filters:
        folders:
          - fieldwork
    design:
      columns: '2'
      view: compact
#  - block: markdown
#    content:
#      title: Team
#      subtitle: '[Colleagues, research buddies, friends](./post/team/)'
#    design:
#      columns: '1'
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content: 
      title: Contact
      subtitle: Fantastic beast and where to find me
      text: |-
        My office hours may vary through the year due to the hybrid work from home/office of the CSIC. Check on my mail if you are planning to visit at least one day in advanced!
      # Contact (add or remove contact options as necessary)
      email: dpastorgalan@csic.es
    #  phone: +34 680534170
    #  appointment_url: 'https://calendly.com'
      address:
        street: Doctor Severo Ochoa 7
        city: Madrid
        region: ''
        postcode: '28040'
        country: Spain
        country_code: ES
      coordinates:
        latitude: '40.443778130903205'
        longitude: '-3.7229560010646727'
      directions: The former morgue of the Medicine Faculty! You can access through the line 6 of the Metro in the Ciudad Universitaria stop.
#       office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#       contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/HotspotTrack'
        #- icon: skype
        #  icon_pack: fab
        #  name: Skype Me
        #  link: 'skype:echo123?call'
       # - icon: video
       #   icon_pack: fas
       #   name: Zoom Me
       #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
#      autolink: true
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
---