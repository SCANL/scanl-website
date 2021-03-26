---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'On the Distribution of "Simple Stupid Bugs" in Unit Test Files: An Exploratory
  Study'
subtitle: ''
summary: ''
authors:
- Anthony Peruma
- Christian D. Newman
tags:
- '"Mining Software Repositories"'
- '"Unit Tests"'
- '"Bugs"'
- '"Simple Stupid Bugs"'
- '"Test Smells"'
categories: []
date: '2021-05-01'
lastmod: 2021-03-17T23:45:07-04:00
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
publishDate: '2021-03-18T03:45:07.062816Z'
publication_types:
- '1'
abstract: A key aspect of ensuring the quality of a software system is the practice
  of unit testing. Through unit tests, developers verify the correctness of production
  source code, thereby verifying the system's intended behavior under test. However,
  unit test code is subject to issues, ranging from bugs in the code to poor test
  case design (i.e., test smells). In this study, we compare and contrast the occurrences
  of a type of single-statement-bug-fix known as s̈imple stupid bugs(̈SStuBs) in test
  and non-test (i.e., production) files in popular open-source Java Maven projects.
  Our results show that SStuBs occur more frequently in non-test files than in test
  files, with most fix-related code associated with assertion statements in test files.
  Further, most test files exhibiting SStuBs also exhibit test smells. We envision
  our findings enabling tool vendors to better support developers in improving the
  maintenance of test suites.
publication: '*Proceedings of the 18th International Conference on Mining Software
  Repositories*'
url_pdf: xxx
doi: xxx
---
