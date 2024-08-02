---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2.5rem"

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
        color:
        image:
          # Add your image background to `assets/media/`.
          filename: 'france.jpg'
          filters:
            brightness: 0.6
          size: cover
          position: center
          parallax: true
  - block: resume-experience
    design:
      # Default section spacing
      spacing: 
    content:
      title: 'Experience'
      subtitle: ''
      text:
    design:
      css_class: dark
      background:
        image:
          filename: 
          size: cover
          position: center
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      background:
        image:
          filename: 'montana.jpg'
          filters:
            brightness: 0.8
          size: cover
          position: center
      view: article-grid
      columns: 3
  - block: collection
    content:
      count: 3
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: date-title-summary
  - block: collection
    id: talks
    content:
      count: 3
      title: Recent Talks
      filters:
        folders:
          - event
    design:
      background:
        image:
          filename: 'mexico.jpg'
          filters:
            brightness: 0.8
          size: cover
          position: center
      view: article-grid
      columns: 3
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: |
        ## <span style="color: white; font-size: 21px;"><center>**2024**</center>
        <div style="width: 80%; height: 0.5px; background: linear-gradient(to right, lightgray, white, lightgray); margin: 10px 0;"></div>

        - - -

        <span style="color: white; font-size: 17px; font-family: Tahoma;">\[May, 2024] <span style="color: LightSeaGreen; font-size: 17px; font-family: Tahoma;">Shovito and Asif received 2024 CHS Student Heat and Health Research Challenge Award.

        - - -

        <span style="color: white; font-size: 17px; font-family: Tahoma;">\[Jan, 2024] <span style="color: LightSeaGreen; font-size: 17px; font-family: Tahoma;">Asif's poster GlyCoach won the best poster award on ASU College of Health Solutions Faculty Research Day.

        - - -

        ## <span style="color: white; font-size: 21px;"><center>**2023**</center>
        <div style="width: 80%; height: 0.5px; background: linear-gradient(to right, lightgray, white, lightgray); margin: 10px 0;"></div>

        - - -

        <span style="color: white; font-size: 17px; font-family: Tahoma;">\[Nov, 2023] <span style="color: LightSeaGreen; font-size: 17px; font-family: Tahoma;">Asif received the NIH T32 Institutional Training Grant for AI in Precision Nutrition (AIPrN) Research.

        - - -

        <span style="color: white; font-size: 17px; font-family: Tahoma;">\[Aug, 2023] <span style="color: LightSeaGreen; font-size: 17px; font-family: Tahoma;">Asif received NSF Student Travel Award to attend IEEE BHI'23 at Pittsburgh, PA.

        - - -
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 4
      # Filter on criteria
      filters:
        author: admin
        category: "news"
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
      background:
        image:
          filename: ''
          filters:
            brightness: 0.8
          size: cover
          position: center
      # Choose a layout view
      view: #date-title-summary
      # Reduce spacing
      #spacing:
        #padding: [5, 0, 0, 0]
  - block: markdown
    content:
      title: 'Contact'
      autolink: true
      subtitle: ''
      text: |-
        <span>&#128238;</span> aarefeen@asu.edu

        <span>&#128315;</span> <a href="https://www.google.com/maps/place/6161+E+Mayo+Blvd,+Phoenix,+AZ+85054/@33.6569784,-111.9518591,17z/data=!3m1!4b1!4m6!3m5!1s0x872b76b5a5c0e105:0xa44ad24e640fc2e4!8m2!3d33.6569784!4d-111.9492842!16s%2Fg%2F11kl5s9jxk?entry=ttu" target="_blank">6161 E Mayo Blvd, Room 319, Phoenix, AZ 85054, USA</a>
    design:
      css_class: dark
      background:
        image:
          filename: 'spain.jpg'
          filters:
            brightness: 0.8
          size: cover
          position: center
---
