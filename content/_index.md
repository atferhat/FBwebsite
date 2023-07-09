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
  - block: features
    content:
      title: Management & Communication Skills
      items:
        - name: Project management
          description: 
          icon: list-check
          icon_pack: fa

        - name: Team leader & Mentoring
          description: 
          icon: people-group
          icon_pack: fa

        - name: Teamwork & collaboration 
          description: 
          icon: globe
          icon_pack: fa

        - name: Adaptability & Initiative
          description: 
          icon: sun
          icon_pack: fa

        - name: Communication
          description: |2-
            Public & Technic
          icon: comments
          icon_pack: fa



  - block: features
    content:
      title: Informatics & Scientific Skills
      items:
        - name: R
          description: 
          icon: r-project
          icon_pack: fab

        - name: Python
          description: 
          icon: python
          icon_pack: fab

        - name: Matlab
          description: 
          icon: matlab
          icon_pack: fab
        
        - name: Scientific watch
          description: 
          icon: newspaper
          icon_pack: fa

        - name: Problem solving
          description: 
          icon: question
          icon_pack: fa


        - name: Data Management
          description: |2-
              - Collection
              - Analysis
              - Visualisation
          icon: database
          icon_pack: fa

        - name: Statistics
          description: |2-
              - Frequentist
              - Bayesian
          icon: chart-line
          icon_pack: fas

        - name: Experiment
          description: |2-
              Design & Analysis
          icon: flask
          icon_pack: fa

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
        - title: Research Scientist
          company: Columbia University, Zuckerman Institute
          company_url: ''
          company_logo: org-gc
          location: New-York, USA
          date_start: '2020-02-01'
          date_end: '2023-02-01'
          description: |2-
              Responsibilities include:

              * Characterized cognitive mechanisms and neural basis of hierarchy in macaques
              * Led a project with cutting edge technology (electrophysiology in vivo, electroencephalograms, eye-tracking)
              * Worked with Bayesian model of model-free/ model-based reinforcement learning
              * Mentored undergraduate and graduate students
              * Contributed to national grant writing (granted) and scientific papers revisions

        - title: Research Scientist
          company: Institut Pasteur
          company_url: ''
          company_logo: org-x
          location: Paris, France
          date_start: '2014-09-01'
          date_end: '2019-07-31'
          description: |2-
              Responsibilities include:

              * Characterized and determine RNA expression in brain related to disorders 
              * Managed differential analysis of large genetic dataset 
              * Characterized animal models for autism spectrum disorder at behavioral, structural and genetic level 
              * Designed new behavioral tasks to study social interactions in rodents
              * Identified new therapeutic targets for autism spectrum disorder

    design:
      columns: '2'
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. in Neurobiology
          company: Université de Paris | Institut Pasteur
          company_url: ''
          company_logo: org-gc
          location: Paris | France
          date_start: '2014-09-01'
          date_end: '2018-09-18'
          description:
        - title: Master in Cell signaling and Neuroscience
          company: Université Paris-Saclay
          company_url: ''
          company_logo: org-gc
          location: Orsay | France
          date_start: '2012-09-01'
          date_end: '2014-08-31'
          description:
        - title: BSc in Neurobiology
          company: University of Leeds
          company_url: ''
          company_logo: org-gc
          location: Leeds | UK
          date_start: '2012-09-01'
          date_end: '2013-08-31'
          description:
        - title: licence in Biology of Health
          company: Université Paris-Saclay
          company_url: ''
          company_logo: org-gc
          location: Orsay | France
          date_start: '2009-09-01'
          date_end: '2012-08-31'
          description:
        
    design:
      columns: '2'    
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplishments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2023-05-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://coursera.org/share/f8089f49b8d89d22e3433fde334dc535
          date_end: ''
          date_start: '2023-03-01'
          description: |2-
            - Data science Tools
            - Python and SQL
            - Machine Learning
          organization: Coursera
          organization_url: https://www.coursera.org
          title: IBM data science
          url: ''
        - certificate_url: https://coursera.org/share/f8089f49b8d89d22e3433fde334dc535
          date_end: ''
          date_start: '2016-01-01'
          description: 'xx'
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Bioinformatics Methods I & II
          url: ''
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'

  - block: collection
    content:
      title: Publications
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
        - name: Professional
          tag: Professional
        - name: Personal
          tag: Personal
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
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

  
  - block: tag_cloud
    content:
      title: Keyword
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I stay available by mail or phone
      # Contact (add or remove contact options as necessary)
      email: at@ferhatberland.com
      phone: +33 6 60 62 31 89
      appointment_url: 'https://calendly.com/at--sxs'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
        # - icon: skype
        #   icon_pack: fab
          # name: Skype Me
          # link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
