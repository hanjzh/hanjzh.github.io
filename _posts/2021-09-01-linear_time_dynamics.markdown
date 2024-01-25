---
layout: post
title:  "Linear-Time Dynamics using Lagrange Multipliers"
date:   2021-09-01 22:21:59 +00:00
image: /images/dactcr.png
categories: projects
author: "Hanna Jiamei Zhang"
code: https://github.com/philip-huang/csc417-project
venue: "Physics Based Animation Course"
writeup: /pdfs/Jul_25_2022_MARSS_DACTCR_FINAL_VERSION.pdf
---
Worked with a fellow student to implement David Baraff's 1996 work on Linear-Time Dynamics using Lagrange Multipliers in MATLAB. Results are demonstrated on 2D serially jointed structures, trees, and closed-loop chain structures. The dynamics of these systems are handled by 3 Different methods 1) standard matrix inversion, 2) a sparse O(n) factorization method, and a 3) dense \textit{O(n$^3$)} factorization method. Comparisons of the performance of these different solvers on the aforementioned systems at varying scales (i.e. size of the structures) were done.