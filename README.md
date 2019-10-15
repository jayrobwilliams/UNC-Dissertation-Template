# UNC Dissertation Template

This repository is a lightly updated version of [Björn B. Brandenburg](https://people.mpi-sws.org/~bbb/)'s UNC dissertation [LaTeX template](https://www.cs.unc.edu/~bbb/), with assistance from [Chelsea Estancona](https://clestancona.wixsite.com/chelseaestancona)'s previous modifications. The changes I made were sufficient to get my dissertation approved by the graduate school on 10/11/2019, but the requirements seem to change every year. To that end, this repository is intended to serve as an open and evolving resource going forward. If you use this template for your own dissertation in future years, please consider forking this repository or submitting a pull request with your changes so that it can stay up to date for future PhD students!

Changes I've made to Björn's template include:
- Making main title standard font size
- Making all chapter, section, and sub(sub)section headings standard font size
- Centering the Table of Contents header
- Making footnotes only 1pt smaller than body text
- Placing chapter numbers and titles on the same line
- Setting 1" top margins for appendix headers
- Removing some of the more bespoke code related to terms and figures in his dissertation from `macros.tex`
- Switching from natbib to regular BibTeX
- Switching from `amsthm` the `ntheorem`
- Adding a comment function at the end of `macros.tex` to allow color highlighted notes set off by brackets in rendered PDFs