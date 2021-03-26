---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On the generation, structure, and semantics of grammar patterns in source code
  identifiers
subtitle: ''
summary: ''
authors:
- Christian D. Newman
- Reem S. AlSuhaibani
- Michael J. Decker
- Anthony Peruma
- Dishant Kaushik
- Mohamed Wiem Mkaouer
- Emily Hill
tags:
- '"Program comprehension"'
- '"Identifier naming"'
- '"Software maintenance"'
- '"Source code analysis"'
- '"Part-of-speech tagging"'
- '"Grammar Pattern"'
categories: []
date: '2020-01-01'
lastmod: 2021-03-17T23:44:59-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-03-18T03:44:58.745226Z'
publication_types:
- '2'
abstract: Identifiers make up a majority of the text in code. They are one of the
  most basic mediums through which developers describe the code they create and understand
  the code that others create. Therefore, understanding the patterns latent in identifier
  naming practices and how accurately we are able to automatically model these patterns
  is vital if researchers are to support developers and automated analysis approaches
  in comprehending and creating identifiers correctly and optimally. This paper investigates
  identifiers by studying sequences of part-of-speech annotations, referred to as
  grammar patterns. This work advances our understanding of these patterns and our
  ability to model them by (1) establishing common naming patterns in different types
  of identifiers, such as class and attribute names; (2) analyzing how different patterns
  influence comprehension; and (3) studying the accuracy of state-of-the-art techniques
  for part-of-speech annotations, which are vital in automatically modeling identifier
  naming patterns, in order to establish their limits and paths toward improvement.
  To do this, we manually annotate a dataset of 1,335 identifiers from 20 open-source
  systems and use this dataset to study naming patterns, semantics, and tagger accuracy.
publication: '*Journal of Systems and Software*'
url_pdf: https://www.sciencedirect.com/science/article/pii/S0164121220301680
doi: https://doi.org/10.1016/j.jss.2020.110740
---
