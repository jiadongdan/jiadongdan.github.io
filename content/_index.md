---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  #- block: about.avatar
  #  content:
  #    # Choose a user profile to display (a folder name within `content/authors/`)
  #    username: admin
  #    text:
  #  design:
  #    background:
  #      color: black
  #      text_color_light: true
  #      image:
  #        # Add your image background to `assets/media/`.
  #        filename: cover_page.png
  #        filters:
  #          brightness: 0.5
  #        size: cover
  #        position: center
  #        parallax: false
  - block: markdown
    content:
      title:
      subtitle:
      text: |-
        <div class="row" style="padding-top: 20px; padding-bottom: 30px;">
         <div class="col-sm-4 d-flex justify-content-center align-items-center">
            <div class="profile-wrapper position-relative" style="width: 180px; height: 180px;">
              <div class="profile-picture-container" style="width: 170px; height: 170px; border-radius: 50%; overflow: hidden;">
                  <img style="width: 100%; height: 100%; object-fit: cover;" src="/authors/admin/avatar.jpg" alt="Profile Picture">
              </div>
              <span class="status-emoji" style="position: absolute; bottom: 20px; right: 15px; font-size: 20px;">☕️</span>
            </div>
         </div>
         <div class="col-sm-8 d-flex flex-column justify-content-center align-items-center align-items-sm-start text-center text-sm-left">
              <h1 class="portrait-title">Jiadong Dan</h1>
              <p class="desc"></p>
                <p style="line-height: 1.5; font-size: 1em;">
                  <span style="font-size: 1em; line-height: inherit; vertical-align: middle;">🤖</span> Eric and Wendy Schmidt AI in Science Fellow<br>
                  <span style="font-size: 1em; line-height: inherit; vertical-align: middle;">🎓</span> National University of Singapore, <span style="font-size: 1em; line-height: inherit; vertical-align: middle;">🇸🇬</span><br>
                  <span style="font-size: 1em; line-height: inherit; vertical-align: middle;">📍</span> Office: 14, Science Drive 4, CBIS, NUS
                </p>
              <ul class="network-icon" aria-hidden="true" style="list-style: none; padding: 0; display: flex; gap: 10px;">
                <li>
                  <a href="https://scholar.google.com/citations?user=U4t214wAAAAJ&amp;hl=en" target="_blank" rel="noopener" aria-label="google-scholar"><i class="ai ai-google-scholar fa-xl"></i></a>
                </li>
                <li>
                  <a href="https://orcid.org/0000-0002-0225-5563" target="_blank" rel="noopener" aria-label="orcid"><i class="ai ai-orcid fa-xl"></i></a>
                </li>
                <li>
                  <a href="https://github.com/jiadongdan" target="_blank" rel="noopener" aria-label="github"><i class="fab fa-github fa-xl"></i></a>
                </li>
                <li>
                  <a href="https://linkedin.com/in/jiadongdan" target="_blank" rel="noopener" aria-label="linkedin"><i class="fab fa-linkedin fa-xl"></i></a>
                </li>
                <li>
                  <a href="/uploads/resume.pdf" target="_blank" rel="noopener" aria-label="cv"><i class="ai ai-cv fa-xl"></i></a>
                </li>
              </ul>
            </div>
        </div>
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