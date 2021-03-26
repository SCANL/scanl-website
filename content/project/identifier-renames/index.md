---
title: Identifier Renames
date: 2021-03-25
summary: "In this project, through a series of studies, we aim to model the relationship between the name of an identifier and the behavior of the source code entity it represents."
draft: false
featured: true
external_link: 
links:
image:
  placement: 1
  focal_point: "Center"
  preview_only: false
---
Identifiers are names (i.e., lexical tokens) that uniquely identify entities in the code (such as classes, methods, variables, etc.). Prior research shows that identifiers contribute to, on average, 70% of a software system's codebase. Hence, the quality of an identifier's name has an integral part to play in the developer's ability to comprehend source code.

To correct bad names, developers must refactor their code, more specifically apply a rename refactoring operation to the poorly named identifier. Furthermore, prior research shows that rename refactorings are among the most frequent refactoring operations applied by developers to the source code. However, there is no guarantee that the new name will be a suitable replacement. In other words, developers can rename a poor identifier name with an equally bad name.

Ideally, the name of an identifier should reflect the behavior of the identifier. Adhering to general coding standards, which includes ensuring identifier names follow a set pattern such as camel case, may improve code readability.  However, if the name of the identifier, even though meeting naming standards, does not reflect the intended purpose of the identifier, there can be negative consequences to maintenance activities. 

In this project, through a series of studies, we aim to model the relationship between the name of an identifier and the behavior of the source code entity it represents. To accomplish this, we first need to understand how developers choose names for identifiers. We can achieve this by studying instances where developers rename existing identifiers in the source code (i.e., rename refactorings). Our proposed model will, theoretically, allow us to provide developers with real-time, context-aware suggestions, and appraisals of identifier names. Our proposed model will reduce the time and costs involved in software maintenance and ensure that production-ready code is readable and understandable before deployment.
