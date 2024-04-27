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
        I am an [Eric and Wendy Schmidt AI in Science Fellow](https://www.schmidtfutures.com/our-work/schmidt-ai-in-science-postdocs/) at the National University of Singapore (NUS), where my work bridges machine learning (ML) and scanning transmission electron microscopy (STEM). Under the guidance of Prof. [Stephen J. Pennycook](https://scholar.google.com/citations?user=UnDfo6sAAAAJ&hl=en), my dissertation focused on using ML to efficiently identify quantum defects in atomic resolution STEM images. In my current postdoctoral role in Asst. Prof. [Duane Loh](https://scholar.google.com/citations?user=UnDfo6sAAAAJ&hl=en), my Ph.D. dissertation pioneered the application of ML techniques to rapidly pinpoint quantum defects in atomic resolution STEM images. Currently, in Asst. Prof. [Duane Loh](https://scholar.google.com/citations?user=UnDfo6sAAAAJ&hl=en)’s research group, my focus is on developing an innovative and interpretable ML framework. This framework is designed to comprehensively characterize a broad spectrum of significant materials, representing them through a hierarchy of structural motifs. Building on my extensive expertise in machine learning and electron microscopy, My goal is to develope an electron microscope copilot system designed to assist materials scientists. This platform aims to enhance the efficiency of materials analysis and deepen the understanding of material disorders by organizing and interpreting structural data effectively.

        <div style="display: flex; align-items: center; justify-content: center;">
          <div style="height: 1px; width: 200px; background-color: #2d3742;"></div>
          <i class="fas fa-star" style="margin: 0 15px;"></i>
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
        **Scanning Transmission Electron Microscopy (STEM)** is an advanced material characterization technique that uses a focused electron beam to scan thin samples, producing atomic-resolution images. Besides imaging, STEM can collect spectral data to analyze material compositions and perform four-dimensional scanning transmission electron microscopy (4DSTEM), which captures diffraction patterns at each scan position. 
    design:
      columns: '1'
---
