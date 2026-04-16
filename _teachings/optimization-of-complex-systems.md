---
layout: course
title: Optimization of Complex Systems - 60h
description: This course provides an understanding of advanced algorithms to tackle general optimization problems.
instructor: Andrea Brilli
year: 2025/2026
term: Spring
location: Mondays Room 48 Via Eudossiana, 18, Roma / Tuesdays Room A5, Via Ariosto, 25, Roma
time: Mondays 14:00-16:00 / Tuesdays 15:00-18:00
course_id: optimization-of-complex-systems
schedule:
  - week: 1
    date: Feb 24
    topic: Course Introduction
    description: Overview of mathematical optimization, course structure, and expectations.
  - week: 1
    date: Feb 27
    topic: Coordinate Search
    description: Basic derivative-free algorithmic structure with convergence analysis
    materials:
      - name: Slides
        url: /assets/pdf/slides/Slides_01_27Feb26.pdf
  - week: 2
    date: Mar 03
    topic: Convergence Analysis
    description: Convergence Analysis of Coordinate descent and globalization strategies
    materials:
      - name: Slides
        url: /assets/pdf/slides/Slides_02_03Mar26.pdf
  - week: 2
    date: Mar 06
    topic: Direct Search
    description: Direct Search and introduction to complexity analysis
    materials:
      - name: Slides
        url: /assets/pdf/slides/Slides_03_06Mar26.pdf
  - week: 3
    date: Mar 09
    topic: Multiobjective Optimization
    description: Introduction to Multiobjective Optimization
    materials:
      - name: Slides
        url: /assets/pdf/slides/Slides_04_09Mar26.pdf
  - week: 3
    date: Mar 10
    topic: Multiobjective Optimization
    description: Objective space structure, convex case, portfolio optimization, scalarization methods
    materials:
      - name: Slides
        url: /assets/pdf/slides/Slides_05_10Mar26.pdf
  - week: 4
    date: Mar 24
    topic: Multiobjective Optimization
    description: Pareto Front approximation without scalarization
    materials:
      - name: Slides
        url: /assets/pdf/slides/Slides_06_24Mar26.pdf
  - week: 4
    date: Mar 27
    topic: Multiobjective Optimization
    description: Quality of Pareto Front approximations
    materials:
      - name: Slides
        url: /assets/pdf/slides/Slides_07_27Mar26.pdf
  - week: 5
    date: Mar 31
    topic: Inequality-constrained Optimization
    description: Introduction and Optimality Conditions
  - week: 6
    date: Apr 13
    topic: Inequality-constrained Optimization
    description: Proof of Fritz-John theorem and introduction to the logarithmic barrier
  - week: 6
    date: Apr 14
    topic: Inequality-constrained Optimization
    description: Sequential Interior methods. Theoretical proof and practical considerations
  - week: 7
    date: Apr 20
    topic: Optimization on Manifolds
    description: Seminar by Diego Scuppa
  - week: 7
    date: Apr 21
    topic: Optimization on Manifolds
    description: Seminar by Diego Scuppa
  - week: 8
    date: Apr 27
    topic: Proximal gradient methods
    description: Seminar by Elisa Trasatti
  - week: 8
    date: Apr 28
    topic: Proximal gradient methods
    description: Seminar by Elisa Trasatti
#    materials:
#      - name: building ...
#        url: /assets/pdf/example_pdf.pdf
#      - name: Slides
#        url: /assets/pdf/example_pdf.pdf
---

## Course Overview

The main goal of this course is to teach you how to design algorithms for different types of optimization problems. We'll dig into both the practical and theoretical sides of:

- Derivative-Free methods
- Constraint-handling techniques
- Multiobjective problems

By the end, you should have the critical thinking skills to figure out when and why certain algorithmic approaches work better than others for a given problem.

Throughout the semester, we'll also bring in guest seminars on various topics to keep things fresh and broaden your perspective.

### Background material

- Multivariate Calculus: [Italian notes](/assets/pdf/Multivariate_calculus_note_Italiano.pdf) [English notes](/assets/pdf/Multivariate_calculus_note_English.pdf)
- Basic concepts of Optimization [Italian notes](/assets/pdf/optimization_notes_Italiano.pdf) [English notes](/assets/pdf/optimization_notes_English.pdf)

### Reference Books

- "Derivative-Free and Blackbox Optimization" by C. Audet and W. Hare [Link](https://link.springer.com/book/10.1007/978-3-319-68913-5)
- "Introduction to Derivative-Free Optimization" by A.R. Conn, K. Scheinberg, and L.N. Vicente [Link](https://epubs.siam.org/doi/book/10.1137/1.9780898718768)
- "Multicriteria Optimization" by M. Ehrgott [Link](https://link.springer.com/book/10.1007/3-540-27659-9)
- "Nonlinear Programming: Sequential Unconstrained Minimization Techniques" by A.V. Fiacco and G.P. McCormick [Link](https://epubs.siam.org/doi/book/10.1137/1.9781611971316)

#### Exam

The exam consists of individual projects where you'll implement optimization methods and explore theoretical topics. You'll share your findings with the class through dedicated seminars. No exceptions, everyone presents.

About the seminars: the topics of the seminars are part of the program of the course, I will ask questions during the final seminars.

You can find the topics of the projects [here](/assets/pdf/Projects_OCS_2026.pdf). The projects can be done individually or you can make groups of maximum two people, the depth of the project will change accordingly. Starting from April 20th, there will be a weekly meeting for each student/group. The meeting are scheduled every Tuesday 13:00-14:00, and every Friday 10:30-13:00, in my office (A115, Via Ariosto). I will provide a template to fill in order to organize each week.
