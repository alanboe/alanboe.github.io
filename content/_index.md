---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-1-15
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'


  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 'Senior Project Manager'
          company: ArchKey Solutions - Technologies
          company_url: 'https://www.archkey.com/'
          company_logo: akt
          location: Plymouth, MN
          date_start: '2024-05-20'
          date_end: ''
          description: |2-
            At Archkey I worked as a low voltage project manager for many medical clinics, the City of Burnsville and the Sphere. These projects included AV systems, access control, CCTV, fiber optic cabling, copper network cabling, ordering material, coordinating material shipments and labor needs. 

        - title: 'Limited Energy Project Manager'
          company: Collins Electric
          company_url: 'https://collinsmn.com/'
          company_logo: collins-logo
          location: St. Paul, MN
          date_start: '2012-1-1'
          date_end: '2020-6-30'
          description: |2-
            In this role I was the project manager for many large senior living buildings and communities along with many large multi-dwelling unit buildings. My responsibilities included designing low voltage systems with owners/general contractors/subcontractors, pricing the installation of theses systems, coordinating manpower and material along with coordination with the different building utilities andservice providers. These systems include voice, data, CCTV, guest entry, access control, fiber optic and CATV cabling.

        - title: 'Safety Coordinator'
          company: Egan
          company_url: 'https://eganco.com/'
          company_logo: egan
          location: Champlin, MN
          date_start: '2012-1-1'
          date_end: '1998-1-1'
          description: |2-
            Planned, coordinated and conducted safety training for general worksite conditions. Provided site specific training for hazards such as confined space, bucket trucks, forklifts, scissor lift and power actuated tools. Conducted monthly safety committee meetings with the goal to improve company safety. Implemented changes of company issued Personal Protection Equipment which increased how often PPE was used and reduced injuries. Helped injured employees return to work as quickly as possible including finding positions to fit within their required work restrictions. This reduced our Experience Mod Rate and reduced insurance costs. Served as company EEO Officer and ensured that the company was in compliance with city, county and state requirements while also working at job fairs and community outreach programs. 

    design:
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
        # - name: AI/ML Cognition
        #   tag: AIML
        # - name: Mechanical Design
        #   tag: Mechanical

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false


      
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'


  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      # subtitle:
      # text: |-
      #   Please reach out, I would love to chat!
      # Contact (add or remove contact options as necessary)
      email: slanboe@gmail.com
      phone: 763 438 4314
      # appointment_url: 'https://calendly.com'
      address:
        # street: "Minneapolis, MN"
        city: Minneapolis
        region: MN
        # postcode: '94305'
        # country: United States
        # country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
