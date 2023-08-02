---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      image:
        filename: neu-banner.jpg
      text: |
          <h2>Intelligent Networks</h2>
          <img src="https://github.com/munsuyog/hugo-website/blob/main/assets/media/inet-logo.png?raw=true" style="width:150px;">
          <br>
          TU Berlin,
          <br>
          FG INET/ EN 18,
          <br>
          Einsteinufer 17,
          <br>
          10587 Berlin,
          <br>
          Phone: +49 30 314 75170,
          <br>
          Fax: +49 30 314 78550

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
      view: card
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
