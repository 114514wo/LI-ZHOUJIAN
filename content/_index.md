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
      button:
        text: Download CV
        url: uploads/resume.pdf
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
        My research focuses on the intersection of artificial intelligence and robotics, with particular interests in autonomous driving systems, reinforcement learning algorithms, and large language models.

        I am currently pursuing my Master's degree in Robotics at the National University of Singapore, where I explore innovative solutions for intelligent navigation, path planning optimization, and computer vision applications in robotic systems.
        
        Feel free to reach out for collaboration opportunities! 😃
    design:
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
    design:
      view: citation
  - block: markdown
    content:
      title: '🏆 Awards & Honors'
      subtitle: ''
      text: |-
        ## Recent Achievements
        
        🥇 **National First Prize** - RAICOM Robotics Developer Competition National Finals (Aug 2023)  
        *Top achievement in national robotics development competition*
        
        🥈 **National Second Prize** - 24th China Robotics and Artificial Intelligence Competition (Aug 2022)  
        *Excellence in robotics and artificial intelligence applications*
        
        🥉 **National Third Prize** - 16th China College Students Computer Design Competition (July 2023)  
        *Innovation in computer software design and development*
        
        🏆 **Provincial First Prize** - 13th Jiangsu Province College Students Robotics Competition (Nov 2022)  
        *Regional excellence in robotics technology and innovation*
    design:
      columns: '1'


---
