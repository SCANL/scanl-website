---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'An Ensemble Approach for Annotating Source Code Identifiers with Part-of-speech Tags'
subtitle: ''
summary: ''
authors:
  - Christian
  - Michael
  - Reem
  - Anthony
  - Mohamed Mkaouer
  - Satyajit Mohapatra
  - Tejal Vishoi
  - Marcos Zampieri
  - Timothy Sheldon
  - Emily
profile: false
tags:
- '"Program Comprehension"'
- '"Software Maintenance"'
- '"Natural Language Processing"'
- '"Part-of-Speech Tagging"'
categories: []
date: '2021-07-20'
lastmod: 2021-07-20T23:45:07-04:00
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
publishDate: '2021-07-20T16:13:47.325359Z'
publication_types:
- '2'
abstract: "This paper presents an ensemble part-of-speech tagging approach for source code identifiers. Ensemble tagging is a technique that uses machine-learning and the output from multiple part-of-speech taggers to annotate natural language text at a higher quality than the part-of-speech taggers are able to obtain independently. Our ensemble uses three state-of-the-art part-of-speech taggers: SWUM, POSSE, and Stanford. We study the quality of the ensemble's annotations on five different types of identifier names: function, class, attribute, parameter, and declaration statement, at the level of both individual words and full identifier names. We also study and discuss the weaknesses of our tagger to promote the future amelioration of these problems through further research. Our results show that the ensemble achieves 75% accuracy at the identifier level and 84-86% accuracy at the word level. This is an increase of +17% points at the identifier level from the closest independent part-of-speech tagger."
publication: '*Transactions on Software Engineering*'
url_pdf: "https://www.peruma.me/publication/2021-tse-tagger/2021-tse-tagger.pdf" 
doi: '10.1109/TSE.2021.3098242'
---
