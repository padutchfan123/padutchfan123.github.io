---
title: "Findings from Gerrymandering Analysis"
last_modified_at: 2025-03-02
categories:
  - Blog
tags:
  - Reproducibility
  - GIScience
  - Planning
  - Analysis
  - Gerrymandering
  - Convex Hull
---
### Findings from analysis
My analysis focused upon the approved districts *from* 2023 intended *for* the 2024 election, `districts23`. Using the correlation matrix approach to visualize the results, I found that there was a positive relationship between minimum bounding circle compactness and absolute convex hull representational difference. There was a negative relationship between convex hull compactness and absolute convex hull representational difference. There was a negative relationship between shape compactness and absolute convex hull representational difference. Shape compactness and convex hull compactness exhibited a positive correlation. With convex hull, compactness was higher for all the districts compared to minumum bounding circle and the shape compactness forumula approaches. Districts 1, 2 and 4 were the least compact in all of the scores. This lack of compactness is very visible when the districts are mapped, as the three districts are quite long and thin. Further, district 2 is packed with Black and African American voters. This is even more true for district 7, which had a higher compactness score, despite likely not being very compact (as it has a thin "arm" extending eastward into Birmingham).

[Link to analysis](https://padutchfan123.github.io/OR-Gerrymander-Alabama/gerrymandering_report.html)

### Reproducibility practice takeaways/points for improvement
The use of a research compendium for this study was a great learning opportunity, that did come with some challenges. After working with the template in this study, I feel much more prepared to utilize it again more effectively. One difficulty of the compendium template for me was simply encountering the larger amount of files, some of which were unneccesary for this study. I found there was some learning curve to get acquanited with the proper way to use each file to document my first steps of the research plan, and it was easy to get lost in the repository. However, since working through this example, I now feel a lot more informed on how to express my research plan for future analyses using this template, and I understand how to correctly release a version with my research plan first in order to document my process before jumping in to analysis. I also experienced some difficulty picking up the workflow for spatial indices in R, so I am excited to continue to practice this skill more in other studies. 