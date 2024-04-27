---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: cover_page.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
        I am an [Eric and Wendy Schmidt AI in Science Fellow](https://www.schmidtfutures.com/our-work/schmidt-ai-in-science-postdocs/) at the National University of Singapore (NUS) working at the intersection of machine learning (ML) and scanning transmission electron microscopy (STEM). Supervised by Prof. [Stephen J. Pennycook](https://scholar.google.com/citations?user=UnDfo6sAAAAJ&hl=en), my dissertation focused on using ML to efficiently identify quantum defects in atomic resolution STEM images. In my current postdoctoral role in Asst. Prof. [Duane Loh](https://scholar.google.com/citations?user=UnDfo6sAAAAJ&hl=en)’s group, I am interested in finding an efficient and explainable ML framework that describes a wide variety of important materials with disorder as a hierarchy of structural motifs.
        <div style="display: flex; align-items: center; justify-content: center;">
          <div style="height: 2px; width: 100px; background-color: black;"></div>
          <i class="fas fa-star" style="margin: 0 20px;"></i>
          <div style="height: 2px; width: 100px; background-color: black;"></div>
        </div>
    design:
      columns: '1'
      css_class: 'my_bio'
---
