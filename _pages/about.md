---
layout: about
title: about
permalink: /
subtitle: <p>Postdoctoral researcher in Operations Research</p>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <a href='https://www.diag.uniroma1.it/en'>DIAG, Sapienza University of Rome</a>

selected_papers: False # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a postdoctoral researcher at the Department of Computer, Control, and Management Engineering (DIAG) at Sapienza University of Rome. My research focuses on derivative-free optimization, nonsmooth optimization, and multi-objective optimization.

I completed my PhD in Operations Research, developing novel algorithms for optimization problems where gradient information is unavailable or unreliable. My work combines theoretical analysis with practical algorithm development and implementation.

I am currently working toward designing a general directional derivative-free algorithmic framework that leverages the advantages of direct search and line-search methods while mitigating their inherent limitations. There might be news soon!

### Research Interests

- Derivative-free optimization methods
- Nonsmooth constrained optimization
- Multi-objective optimization
- Numerical algorithms and convergence analysis

### Teaching

I teach courses in mathematical programming and optimization methods at the university level.

### My Projects

#### [log-ds](https://github.com/brilliandrea/logds/releases)

A Matlab implementation of derivative-free direct search methods. The algorithm is able to address general nonconvex constrained optimization problems with a penalty-interior point method, addressing non-relaxable constraints if necessary. The performance is enhance by quadratic models and simplex gradients. The implementation is undergoing a cleaning stage for an official release, but a pre-release is available if anyone is curious.
For anyone interested in testing the algorithm, send me an e-mail and we can set things up together!

#### [log-dfl](https://github.com/DerivativeFreeLibrary/LOGDFL)

A Python implementation of a derivative-free line-search method for general nonconvex constrained optimization problems.
As for log-ds, send me an e-mail for any support!
