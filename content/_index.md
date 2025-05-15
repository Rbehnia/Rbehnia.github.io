---
# Leave the homepage title empty to use the site title
title: "Rouzbeh Behnia"
date: 2022-10-25
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      #button:
        #text:
        #url: 
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
    id: news
    content:
      title: '📣 NEWS'
      subtitle: ''
      text: |-
        * <span style="color:red; font-size:16px;"> **May. 2025:**</span> <span style="font-size:16px;">Our paper on <a href='https://arxiv.org/abs/2505.07148' target='_blank'> dropout-resilient secure aggregation for federated learning in 5G networks </a> was accpeted in  **ACM WiSec 2025**</span>
        * <span style="color:red; font-size:16px;"> **May. 2025:**</span> <span style="font-size:16px;">Our paper on interactive framework for privacy-preserving FL won the BEST PAPER AWARD in **IEEE S&P Workshops**</span>
        * <span style="color:red; font-size:16px;"> **Mar. 2025:**</span> <span style="font-size:16px;">Our paper on interactive framework for privacy-preserving FL was accepted to **IEEE S&P Workshops**</span>
        * <span style="color:red; font-size:16px;"> **Oct. 2024:**</span> <span style="font-size:16px;">Our attack paper on MicroSecAgg (PoPETS 2024) was accepted to **ICDM MLC Workshop**</span>
        * <span style="color:red; font-size:16px;"> **Sep. 2024:**</span> <span style="font-size:16px;">Our paper on fixed-size mini batches for Rényi differential privacy was accepted to **NeurIPS 2024**</span>
        * <span style="color:red; font-size:16px;"> **Aug. 2024:**</span> <span style="font-size:16px;">Our paper on secure aggregation for federated deep learning was accepted to **ACSAC 2024**</span>
        * <span style="color:red; font-size:16px;"> **Apr. 2024:**</span> <span style="font-size:16px;">Our paper on multi-user searchable encryption was accepted to **USENIX 2024**</span>
    design:
      css_style: "max-height: 400px; overflow-y: scroll; padding: 10px; border: none; width: 70%; margin: 0 auto;"
     #columns: '1'
  - block: collection
    id : papers
    content:
      title: Recent Publications
      text: "For a complete list of publications, please visit my <a href='https://scholar.google.com/citations?user=1DlmPcQAAAAJ&hl=en&oi=ao' target='_blank'>Google Scholar</a>"
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: "
        **Fall 2024**
        
        - ISM 4263/6930 Cloud Solution Architecture"
  # - block: collection
  #   id: newss
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
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
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: markdown
  #   id: pubs
  #   content:
  #     title: 'Publications'
  #     subtitle: ''
  #     text: |-
  #       * <span style="color:red; font-size:16px;"> **Sep. 2024:**</span> <span style="font-size:16px;">Invited to serve on an **NSF Panel**</span>
  #       * <span style="color:red; font-size:16px;"> **Sep. 2024:**</span> <span style="font-size:16px;">Our paper on fixed-size mini batches for Rényi differential privacy was accepted to **NeurIPS 2024**</span>
  #       * <span style="color:red; font-size:16px;"> **Aug. 2024:**</span> <span style="font-size:16px;">Our paper on secure aggregation for federated deep learning was accepted to **ACSAC 2024**</span>
  #       * <span style="color:red; font-size:16px;"> **Apr. 2024:**</span> <span style="font-size:16px;">Our paper on multi-user searchable encryption was accepted to **USENIX 2024**</span>
  #   design:
  #     css_style: "max-height: 400px; overflow-y: scroll; padding: 2px; border: none; width: 100%; margin: 0 auto;"
  #     view: citation
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
