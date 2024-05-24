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
        I am an [Eric and Wendy Schmidt AI in Science Fellow](https://www.schmidtfutures.com/our-work/schmidt-ai-in-science-postdocs/) at the National University of Singapore (NUS), specializing in the intersection of machine learning (ML) and scanning transmission electron microscopy (STEM). Guided by Prof. [Stephen J. Pennycook](https://scholar.google.com/citations?user=UnDfo6sAAAAJ&hl=en), my Ph.D. research innovatively applied ML to identify quantum defects in atomic resolution STEM images. Now in Asst. Prof. [Duane Loh](https://www.physics.nus.edu.sg/faculty/loh-duane/)'s group, I am advancing a robust ML framework to characterize materials through a hierarchy of structural motifs. Leveraging my deep expertise, I aim to develop an *electron microscope copilot system* to improve material analysis and enhance understanding of material disorders.

        <div style="display: flex; align-items: center; justify-content: center;">
          <div style="height: 1px; width: 200px; background-color: #2d3742;"></div>
          <i class="fas fa-atom" style="margin: 0 20px;"></i>
          <div style="height: 1px; width: 200px; background-color: #2d3742;"></div>
        </div>
    design:
      columns: '1'
      css_class: 'my_bio'

  - block: markdown
    content:
      title:
      subtitle:
      text: |-
        ### What is Scanning Transmission Electron Microscopy?
        **Scanning Transmission Electron Microscopy (STEM)** is an advanced material characterization technique that uses a focused electron beam to scan thin samples, producing *atomic-resolution images*. Besides imaging, STEM can collect  *spectral data* to analyze material compositions and perform four-dimensional scanning transmission electron microscopy (*4DSTEM*), which captures diffraction patterns at each scan position.
        
        <!--### An Intelligent Electron Microscope Copilot-->

        <!--### Approach and Significance-->
        
        <!--### A Road Map to-->

    design:
      columns: '1'
---
