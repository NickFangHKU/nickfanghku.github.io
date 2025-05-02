---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Under construction now
    design:
      spacing:
        padding: ['20px', '60px', '20px', '60px']
  
  - block: markdown
    content:
      title: Lab of Scalable and Sustainable Photonic Manufacturing
      subtitle: "Professor Nicholas Fang's Research Group"
      text: |
        Professor Fang is trained as an applied physicist and educator with focus on optical and acoustic materials. Built upon our unique and world-leading expertise in advanced wave functional materials, Professor Fang's new research team of sustainable nanophotonics at HKU will launch the following research efforts:
        1. Can photonic manufacturing boost the sustainability and efficiency of catalytic conversion?
        2. Can photonic manufacturing enhance the sustainability of networked devices and systems integrated with traditional fibers, yarns, and textiles?
        3. Can 3D organ-on-chip tissue models by photonic manufacturing fully recapitulate the patient-specific evolution of age-related diseases?

        Specialties: photonics, nanofabrication, advanced imaging technology
        
        We invite you to take a look at the publications to get a better idea of our previous research. Feel free to get in touch with Professor Fang to say hi or for more information.
    design:
      spacing:
        padding: ['20px', '40px', '20px', '40px']
  
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: 800px
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000
      spacing:
        padding: ['20px', '20px', '20px', '20px']
 
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        # publication_type: 'article'
    design:
      view: citation
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
