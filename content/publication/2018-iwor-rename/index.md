---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Empirical Investigation of How and Why Developers Rename Identifiers
subtitle: ''
summary: ''
authors:
- Anthony Peruma
- Mohamed Wiem Mkaouer
- Michael J. Decker
- Christian D. Newman
tags:
- '"Program comprehension"'
- '"Rename refactoring"'
- '"natural language processing"'
- '"Refactoring"'
categories: []
date: '2018-01-01'
lastmod: 2021-03-17T23:45:03-04:00
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
publishDate: '2021-03-18T03:45:02.746089Z'
publication_types:
- '1'
abstract: Renaming is vital to software maintenance and evolution. Developers rename
  entities when their original names no longer fit their behavioral role within the
  program. This may happen if the entity's original name was of poor quality or if
  the system has evolved such that the original name needs to be updated to reflect
  some of this evolution. In the end, the reason for the rename ultimately falls under
  increasing understandability and comprehension. Because comprehension is so important,
  and identifiers are the primary way developers comprehend code, it is critical to
  understand empirically how and why identifier names evolve. Armed with an understanding
  of these two facets of identifier evolution, researchers will be able to train algorithms
  to recognize, recommend, or even automatically generate high-quality identifier
  names. We present an empirical study of how method, class and package identifier
  names evolve to better understand the motives of their evolution. The empirical
  validation involves a set of 524,113 rename refactorings, performed on 3,795 Java
  systems. In a nutshell, our findings demonstrate that most rename refactorings narrow
  the meaning of the identifiers for which they are applied. Further, we analyze commit
  messages to contextualize these renames.
publication: '*Proceedings of the 2nd International Workshop on Refactoring*'
url_pdf: https://doi.org/10.1145/3242163.3242169
doi: 10.1145/3242163.3242169
---
