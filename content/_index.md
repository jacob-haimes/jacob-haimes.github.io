---
title: 'Home'
type: landing

sections:
  - block: resume-biography
    content:
      title: Jacob Haimes
      text: 
      # image:
      #   file: logo
      # primary_action: 
      #   text: My Work
      #   url: /all/
      #   icon: custom/podcast
      # secondary_action:
      #   text: Experience
      #   url: /about/
    design:
      no_padding: true
      spacing:
        padding: [0, 0, 1em, 0]
        margin: [0, 0, 1em, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "#1B4066"
        image:
          # Add your image background to `assets/media/`.
          filename: jacob-haimes-banner-6.5L-min-2.jpeg
          filters:
            brightness: 0.6
  - block: text-center-markdown
    content: 
      # title:
      # subtitle:
      text: <div>Jacob Haimes is aspiring towards a career in research and scientific communication regarding transformative technologies, with the intent of making cutting edge developments accessible to the general public. He received a BS in Mechanical Engineering and an MS in Computational Modeling from CU Boulder.</div>
      # <div class="mt-4 bg-primary-900 rounded-2xl" style="margin-left:5rem; margin-right:5rem;"><div class="pt-4 pb-4 px-6"><strong>Technological developments today are going to have massive repercussions on both the near and long-term future; everyone has a right to be part of the conversations surrounding them.</strong></div></div>
    design:
      spacing:
        padding: ["1rem", ".5rem", "1rem", ".5rem"]
        margin: [0, 0, 0, 0]
  - block: main-collection
    content:
      title: Featured Work
      # subtitle: ''
      # text: ''
      count: 3
      filters:
        folders:
          - work
        # author: ""
        # category: ""
        # tag: ""
        # publication_type: ""
        featured_only: true
        # exclude_featured: false
        # exclude_future: false
        # exclude_past: false
      archive:
        text: Check out more content
    design:
      view: main-article-grid
      spacing:
        padding: [".5rem", 0, ".5rem", 0]
        margin: [0, 0, 0, 0]
---
