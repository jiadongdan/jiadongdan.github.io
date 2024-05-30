---
# Leave title empty to use the site title
title:
date: 2022-05-30
type: landing

sections:
  # PI 
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
                  <span style="font-size: 1em; line-height: inherit; vertical-align: middle; display: inline-block; width: 1.2em; text-align: center;">🤖</span> Eric and Wendy Schmidt AI in Science Fellow<br>
                  <span style="font-size: 1em; line-height: inherit; vertical-align: middle; display: inline-block; width: 1.2em; text-align: center;">🎓</span> National University of Singapore, 🇸🇬<br>
                  <span style="font-size: 1em; line-height: inherit; vertical-align: middle; display: inline-block; width: 1.2em; text-align: center;">📍</span> Office: 14, Science Drive 4, CBIS, NUS
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


# this page will be rendered but not listed
_build:
  render: never
cascade:
  _build:
    render: never
    list: always
---