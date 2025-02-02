---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Disal
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Disal Research Group** is a center of excellence in Machine Learning research. Our work spans applications in public health, agriculture, biometrics, human emotions, and image processing.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  


  - block: collection
    content:
      title: Latest Journal Articles
      text: "Explore our journal articles, showcasing cutting-edge research from our lab."
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: "Advancing AI for a Better Future"
      subtitle: |
        The Disal Research Group is dedicated to pioneering advancements in Machine Learning with real-world impact.  
        
        Our research spans public health, precision agriculture, biometric security, affective computing, and image processing, leveraging AI to solve complex challenges.  
        
        Through innovative methodologies and interdisciplinary collaboration, we develop intelligent systems that enhance human well-being, optimize resources, and push the boundaries of AI-driven solutions.

      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
