Get Organized!
========================================================
author: Matthew Stephens
date: 3/13/2017
autosize: true

Main Thesis
========================================================

- Organization boosts productivity and impact
- I should get organized (and so should you!)


Motivation: Reproducibility
============================

- Principle: when publishing results of computational procedures, we should
publish the code that produced the results. (Buckheit and Donohoe)
- "publishing figures or results without the complete software environment could
be compared to a mathematician publishing an announcement of a mathematical theorem without giving the proof" (Buckheit and Donohoe)
- “an article about a computational result is advertising, not scholarship. The actual scholarship is the full software environment, code and data, that produced the result.” (Claerbout)


Organization I: Research Project Websites
========================================================

- Goal: When I (or my students) publish a paper, we have a website and code
that documents how we got there.
- Examples:
    - [ash](../../../../../ash-packrat-test/analysis/index.html)
    - [fast-ash](../../fast-ash/docs/index.html)
    - [truncash](../../truncash/docs/index.html)




Benefits: Beyond Reproducibility
========================================================

- Details are preserved.
- Failed experiments are preserved.
- Next steps are easier ("extensible research")
- By writing early on, you sharpen your thinking.


Getting it Done
========================================================

- This goal must be baked into the way you do research!
- Practical Steps:
  - Use notebooks (knitr/Rmarkdown/Rstudio; ipython/jupyter)
  - Become a git novice. (Software carpentry)
  - Use `workflowr` (R package)
      - https://github.com/jdblischak/workflowr
      - Credit: John Blischak



Organization II: Dynamic Statistical Comparisons
========================================================

- Current system of publishing methods comparisons in papers is horribly inefficient.
- Everyone has to repeat the same work!
- Everyone hates tuning other peoples methods! (and isn't very good at it...)
- No-one trusts the results!


Dynamic Statistical Comparisons
================================

Imagine if comparisons and benchmarks were *organized* to make it
easy to:
- Add new methods
- Add new scenarios (eg simulations)
- Add new scores


Benefits
========

- Everyone can run their own methods.
- Noone has to run other peoples methods! ("Carrot for Reproducibility")
- Transparency.
- Collaboration through Competition


Getting it Done
========================================================

Various recent R packages faciliate running comparisons.
- `dscr` (Dynamic Statistical comparisons in R)
- `BatchExperiments`
- `simulator`

But there is work to be done...


dscr: DSC in R
=================

Divides comparisons into three steps: simulate, apply methods, score
- Simulate: produces `input` and `metadata`
- Methods: turn `input` into `output`
- Scores: compare `output` with `metadata`


Runs all methods on all simulations, and applies all scores; saves results.

Example: normal means problem [http://github.com/stephens999/dscr-normal-means](../../dscr-normalmeans/docs/index.html)


<!---[vignette](file:///Users/stephens/Dropbox/Documents/git/dscr/vignettes/one_sample_location.html)
-->

What we learned
===================

- Automating book-keeping of these comparisons is very attractive!
- Requiring generic names for variables ("input", "output") makes code harder to read and write
- sometimes want more flexibility than three-steps
    - e.g. RNAseq pipelines with several steps
- often want to interface with other software, not just `R`.

In current work (DSC2; Gao Wang) we are developing a more flexible system.


Challenges Ahead
=================

- Getting people (you!) to contribute
- Summarizing results of complex comparisons
- Sharing large results files


More Information
================

- `workflowr`: http://github.com/jdblischak/workflowr
- `dscr`: http://github.com/stephens999/dscr
- `DSC2`: http://github.com/stephenslab/dsc2


