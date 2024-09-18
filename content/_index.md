---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'About Me'
      subtitle: ''
      text: |-
        I received extensive training from world-renowned institutions to lead projects successfully published in international scientific journals. My professional experience has given me the ability to interact with collaborators and to bring everyone's capacities towards the same objective as well as to be the representative of the project at international meetings. As well, I characterized and quantified heterogeneous datasets where I used my expertise in different statistical tools, (e.g. statistical models, machine learning, Bayesian statistics approach), as well as analyze of large dataset (e.g. RNA sequencing, brain waves, behavior). 
          {style="text-align: justify;"}
    design:
      columns: '1'
      size: cover
      position: center
      parallax: false
      
  - block: experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: '2006'
      # Education or Experience section first?
      is_education_first: false

  - block: experience
    id: education
    content:
      username: admin2
    design:
      # Hugo date format
      date_format: '2006'
      # Education or Experience section first?
      is_education_first: false
  
  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3


  - block: skills
    id: skill
    content:
      title: Scientifics Skills
      username: admin
    design:
      view: card
      columns: '1'
      show_skill_percentage: false

  - block: skills
    id: skill
    content:
      title: Informatics Skills
      username: adminskill2
    design:
      view: card
      columns: '1'
      show_skill_percentage: false

  - block: skills
    id: skill
    content:
      title: Management & Communication Skills
      username: adminskill3
    design:
      view: card
      columns: '1'
      show_skill_percentage: false
      
  - block: resume-languages
    content:
      title: Languages
      username: admin

#  - block: awards
#    content:
#      title: Accomplishments
#      username: admin

  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: skills
    id: hobbies
    content:
      title: Hobies
      username: admin2
    design:
      show_skill_percentage: false
---
