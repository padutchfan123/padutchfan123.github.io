---
title: "Findings from Tuholske et al. (2024) Reproduction"
last_modified_at: 2025-05-18
categories:
  - Blog
tags:
  - Reproducibility
  - GIScience
  - Planning
  - Analysis
  - Heat
  - Prisons
  - Tuholske
  - Reproduction
---
My final [project](https://padutchfan123.github.io/tuholske-et-al-reproduction/) in Open Source GIScience was a reproduction of [Hazardous heat exposure among incarcerated people in the United States](https://www.nature.com/articles/s41893-024-01293-y), an article in the journal *Nature*, which I worked through with my classmate [Matthew Mills](https://github.com/mkahngmills). 

This was a very interesting paper to attempt to reproduce for many reasons. It was a very short paper (excluding supplementary materials) that detailed its analytical methods and data sources briefly and in a somewhat vague way. However, it did have a open github repository that was clearly modeled in a way that took reproducibility into some consideration. This was interesting to examine, because despite the repository's template, the author's code and analysis was not organized in a very reproducible way, compared to our use of an organized repository, with documented metadata and sustainable code using `groundhog`. This paper definitely would benefit from a reproduction for several reasons, including the author's use of older packages (some of which are not functional anymore), and clear threats to validity (highlighted in the reproduction report's discussion section). 

It was challenging to figure out the best way to approach constructing an analysis plan for this reproduction, because of how confusing the authors' methods were. Documenting the metadata was a useful exercise for us as it allowed us to realize that it would be difficult to identfy the lineage of some of the data provided by the author. In our [pre-analysis plan](https://padutchfan123.github.io/tuholske-et-al-reproduction/docs/report/preanalysisplan_v1.0.html), we attempted to outline what steps of the author's original workflow may be feasible to reproduce, as well as several deviations that would better explore threats to validity.

In our final report, we were able to use the author's code (with some deviations) to reproduce Figure 1 from the original paper, as well as some figures for our planned deviations. This project was a really interesting learning experience overall, and I hope to return to it in the future to continue to improve and polish this repository!

[Current version of report](https://padutchfan123.github.io/tuholske-et-al-reproduction/docs/report/report.html)