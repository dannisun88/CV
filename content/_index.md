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
      css_class: light
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background1.jpg #stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0px', '0', '20px', '0'] 
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # 以下是publications
  - block: collection
    id: papers
    content:
      title: '📜 Publications'
      text: ""
      filters:
        folders:
          - publication
        # exclude_featured: false
    design:
      view: citation
  # 以下是working papers
  - block: markdown
    id: workings
    content:
      title: '📒 Working Papers'
      subtitle: ''
      text: |-
        Wang, Y., Wong, I. A., Sun, D.* (2024). Quiet Quitting: A Scale Development among Tourism/Hospitality Employees. International Journal of Hospitality Management. Under review. 

        Sun, D., Wong, I. A., Xiong, X. (2024). Do Tourists Prefer Dialectal Service? The Role of Processing Fluency, Distinctiveness, and Cultural Learning Cues. Tourism Management. Manuscript completed and to be submitted. 

        Sun, D., Wong, I. A., Xiong, X. (2024). Cutting Edges Meets Silver Tongue: Understanding the Word-of-machine Effect on Hospitality Service. Tourism Management. Methodology completed and manuscript being revised.

        Sun, D., Wong, I. A., Xiong, X. (2024). Paradox of selfie taking: Do tourists prefer selfie, toyfie or avatarfie (or titled when the real-word becomes the digital-twin, the digital-world becomes the reality twin). Tourism Management. Methodology completed and manuscript being drafted.

        Wong, I. A., Huang. J. D., Sun, D. (2024). Boosting Courage in Dealing with Uncivil Customer Behavior: The Role of AI in Service. International Journal of Hospitality Management. Methodology completed and manuscript being drafted.

        Sun, D., Wong, I. A., Wang J. (2024). Song of the Sirens: Paradox of artificial hallucination awareness. Tourism Management. Methodology in progress

        Huang. G. I., Wong, I. A., Sun, D. (2024). Generative AI Recommendation Acceptance. Tourism Management. Methodology in progress 

        Wang, Y., Wong, I. A., Sun, D. (2024). The impacts of job characteristic on intent to leave and employee mental health: The moderating role of quiet quitting. Methodology in progress

        Sun D., Xiao X., Wong, I. A. (2024). Toystagramming: the role of toys in travel encounter. Methodology in progress

        Wong, I.A., Sun D. (2024). Toyfie on the Go: Exploring the phenomenon of sharing toy-fueled tourisdm experience among kidults. (About to commence)

        Wong, I.A., Sun D. (2024). Revolutionizing AI Influencer Marketing: Embracing Truth, Goodness, and Beauty. (About to commence)

        Wong, I. A., He Y., Sun D. (2024). What are you going to wear today? (About to commence)
    design:
      columns: '1'
  # 以下是awards
  - block: collection
    id: awards
    content:
      title: '🏅 Awards'
      text: ""
      filters:
        folders:
          - project
    design:
      view: card
      fill_image: false
      columns: 2
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
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
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
