---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: "Source Code Analysis and Natural Language Lab"
      image:
        filename: lab_icon.png
      text: |
        <br>
        
        SCANL is a diverse team of scientists dedicated to studying the latent connection between source code behavior and the natural language elements used to describe that behavior. 
  - block: markdown
    content:
      title: "Interests"
      text: |
        **Program Comprehension and Textual Analysis.** 

        There is a strong relationship between the natural language (e.g., found in identifiers) and behavior of source code; developers use this relationship to understand the code they read daily. We explore this relationship by studying rename refactorings, grammar patterns, and static source code analysis. Our goal is to support stronger techniques to automate identifier naming as well as support developers in reading and comprehending code more quickly. This is the research topic that underlies all other research we do. Please check our core research section to see what recent work we have done in this area.

        **Program Transformation and Refactoring**

        Program transformations allow us to modify code programmatically. It is important to ensure these techniques are safe, customizable, and easily integrated with today's software development processes such that developers can, for example, migrate APIs or refactor. We support transformations both through our research on identifier naming and through the creation of flexible, easy-to-use techniques for creating and applying program transformations.

        **Static Source Code Analysis**

        A lot of our work relies on static analysis techniques, and most frequently we make use of the srcML Framework to normalize, transform, and analyze source code. Our lab supports several tools built on [srcML](https://www.srcml.org/) in addition to hosting Dr. Emily Hill's natural language framework, [SWUM](https://github.com/SCANL/SWUM). We are dedicated to providing high-quality research tools and data sets for software research and development. Check our [Github](https://github.com/SCANL) page regularly to see what we have to offer and feel free to contact us with questions. 
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
  

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---