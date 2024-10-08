---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
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
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm a passionate researcher and educator with a focus on artificial intelligence, machine learning, and their applications in critical domains such as finance, defense, and healthcare. My expertise spans across various areas, including large foundation models, multi-modal AI, robustness and safety in AI systems, and agentic AI design.

        As an Associate Professor in the Computer Science Department and IHMC-UWF Intelligent Systems & Robotics Department at the University of West Florida, I lead research initiatives in AI assurance, safety, and efficiency. My work aims to develop robust, safe, and adaptable AI systems that can operate effectively in complex and high-stakes environments.

        I'm deeply committed to advancing the field of AI, with a particular focus on making large AI models more efficient and secure. My research often involves exploring techniques such as hardware-software co-design, distillation, quantization, and pruning to optimize and shrink large models without compromising their performance. I'm also keenly interested in adversarial AI and developing methods to ensure model safety for critical applications.

        My work often involves interdisciplinary collaborations, bridging the gap between theoretical concepts and practical applications. Whether it's developing novel approaches for AI robustness, exploring the intricacies of agentic AI design, or investigating the ethical implications of AI in critical sectors, I'm always eager to push the boundaries of what's possible in AI research and development.

        If you're interested in large language models, multi-modal AI, AI safety and robustness, or the future of efficient and secure AI systems, I'd love to connect and discuss potential collaborations or research opportunities!
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      # Add these lines:
      filename: publications.bib
    design:
      view: citation
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
---
