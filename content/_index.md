---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-01-26
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    #design:
      #css_class: dark
      #background:
        # image:
        #   # Add your image background to `assets/media/`.
        #   filename: stacked-peaks.svg
        #   filters:
        #     brightness: 1.0
        #   size: cover
        #   position: center
        #   parallax: false
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research focuses on the development of tools to make decisions with societal implications. This ranges from developing algorithms for online team formation, finding ways to fairly distribute goods in settings such as public health and education where the normative allocation criteria are often at odds, and using statistical tools from causal inference to estimate the effectiveness of an intervention that propogates through a social interference network. I seek to understand the combinatorial structure inherent in all of these problems so that I can leverage it to design better algorithms and estimators. 
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 0
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: talks
    content:
      title: Talks and Posters
      filters:
        folders:
          - event
      count: 4
    design:
      view: date-title-summary
      columns: 1
  - block: markdown
    id: teaching
    content: 
      title: 'Teaching Experience'
      subtitle: ''
      text: |-
        In Spring 2025, I am co-teaching [CS 2110](https://www.cs.cornell.edu/courses/cs2110/2025sp/): *Object-Oriented Programming and Data Structures* with [Curran Muhlberger](https://www.cs.cornell.edu/~curran/). 

        In Fall 2024, I taught CS 2800, now called *Mathematical Foundations of Computing*.

        In Fall 2023, I co-taught CS 2800, previously called *Discrete Structures* with [Noah Stephens-Davidowitz](https://www.noahsd.com/).

        In Summer 2023, I taught ENGRI 1101: *Engineering Applications of Operations Research* as part of Cornell's [Pre-Collegiate Summer Scholars Program](https://sce.cornell.edu/courses/roster/pssp).

        In Fall 2022, I co-taught CS 2800 with [Alexandra Silva]("https://alexandrasilva.org/#/main.html").
        
        <br>
        In addition, I have been a teaching assistant for the following courses:
        
        ### Cornell University
        
        - CS 2111: Programming Practicum, Java (Spring 2022)
        - CS 4820: Introduction to Analysis of Algorithms (Fall 2021)
        - MATH 1106: Modeling with Calculus for the Life Sciences (Spring 2020, 2021)
        
        
        ### University at Buffalo
        
        - CSE 250: Data Structures in C++ (Spring 2017, 2018)
        - CSE 191: Discrete Mathematics (Fall 2017)
        - MTH 241: Multivariable Calculus (Spring 2017)
        - MTH 141: Introductory Calculus (Fall 2016)
        
        
        Finally, I have had positions through the Cornell Math Department's [Active Learning Initiative](https://e.math.cornell.edu/sites/activelearn/) and the Cornell Computer Science Department to develop [course materials](materials/about/).
      
---
