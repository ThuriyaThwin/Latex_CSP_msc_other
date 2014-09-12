# Evaluating the in-the-middle algorithm in constraint satisfaction

Master's thesis, Simon Sigurdhsson, 2014.

## Abstract

The fields of graphical modelling and constraint satisfaction have been very active in recent years, which is unsurprising given the large range of problems which may be described using such techniques. While many novel algorithms have been presented, there are still areas of the field in which improvements are possible. Reviews have uncovered strong links between the linear programming and graphical modelling fields, and it is therefore of interest to survey the possible application of linear programming methods to graphical models and constraint satisfaction problems.

The in-the-middle algorithm, an approximate solution method in linear programming which has seen extensive use in the industry, was extended to max-sum problems by *Grohe and Wedelin (2008)*<sup>†</sup>. Graphical models and constraint satisfaction problems are easily translated into max-sum formulations, and the in-the-middle algorithm is therefore an ideal candidate in reformulating linear programming algorithms to the field of constraint satisfaction.

This thesis presents an implementation of the in-the-middle algorithm applied to max-sum problems, which may be applied to general constraint satisfaction instances. The implementation is benchmarked against three existing high-performance exact solvers in the field, using a problem set consisting of several hundred problems. Results indicate that the in-the-middle algorithm may have potential in the fields of constraint satisfaction and graphical model optimization, but that further research is required to make the algorithm competitive. Several avenues for further research on the algorithm are proposed.

<small>†. Grohe, B., and D. Wedelin. 2008. “Cost Propagation — Numerical Propagation for Optimization Problems.” In *Integration of AI and OR Techniques in Constraint Programming for Combinatorial Optimization Problems*, edited by L. Perron and M. A. Trick, 5015:97–111. Lecture Notes in Computer Science. Berlin, Heidelberg: Springer. ISBN: 978-3-540-68154-0. DOI: `10.1007/978-3-540-68155-7_10`.</small>

## Compiling the thesis

This thesis uses a fair number of modern LaTeX tools. If you've got a recent TeX distribution (*i.e.* TeXLive/MacTeX 2013 or later) you should have most prerequisites, but you will need to download and install the [`chs-msc-thesis`][chs-msc-thesis] package first. After doing so, you should be able to compile the thesis by running `arara report.tex` in the root directory of the cloned repository.

[chs-msc-thesis]: https://github.com/urdh/chs-msc-thesis

## Licensing

The work herein is Copyright 2014 Simon Sigurdhsson.
**No rights are given to reproduce or modify this work.**
