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
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: Moon.svg
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
        My research focuses on logics and formal methods for strategic reasoning, modelling, and verification in Multi-Agent Systems. 
        
        I investigate quantitative, stochastic, and imperfect-information aspects of strategic and temporal logics, with application to mechanism design. 

        ⚠️ Website under construction, [old website](https://www.munyque.com/) ⚠️ 
  
    design:
      columns: '1'
  #- block: collection
    #id: papers
    #content:
    #  title: Featured Publications
    #  filters:
    #    folders:
    #      - publication
    #    featured_only: true
    #design:
    #  view: article-grid
    #  columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: markdown
    content:
      title: Recent News
      text: |
        - 📖 Guest editor for a special issue of [Information and Computation](https://www.sciencedirect.com/special-issue/321808/logical-aspects-of-multi-agent-systems-and-strategic-reasoning-lamassr-2024)
        - 🇦🇺 Co-chair of the Doctoral Consortium @ KR 2026
        - 🇦🇺 Paper accepted at KR 2025
        - 🇺🇸 My AAMAS 25 papers are now available:
          - ["Rational Capability in Concurrent Games"](https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p1309.pdf)
          - ["Changing the Rules of the Game: Reasoning about Dynamic Phenomena in Multi-Agent Systems"](https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p829.pdf)
          - ["Robust Strategies for Stochastic Multi-Agent Systems"](https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p2437.pdf) (extended abstract)
        - 📢 Our AIJ paper ["Formal Verification and Synthesis of Mechanisms for Social Choice"](https://www.sciencedirect.com/science/article/pii/S000437022400208X) is available in open access
    design:
      style: default

# OLD news version
# - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
      # Page type to display. E.g. post, talk, publication...
#      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
      # Choose a layout view
#      view: date-title-summary
      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]

---
