# Notes on R Markdown and Bookdown

**[Matthew Aldridge](https://mpaldridge.github.io)**

This page consists of various notes I've made on R Markdown and Bookdown for creating accessible mathematics lecture notes.

- **R Markdown** is a method to produce documents using Markdown formatting, including LaTeX-style equations, and which can incorporate R code.
- **Bookdown** is an extra package for R Markdown which adds extra features useful for long documents, like spliting the document into multiple interlinked webpages and introducing LaTeX-like theorem environments.

## My  brief introduction to R Markdown and Bookdown

* **[A brief introduction to RMarkdown and Bookdown](https://mpaldridge.github.io/rmarkdown-bookdown/)** This is from summer 2020, and is now a little bit out of date. For example:
   - It is now recommended to use `::: {.theorem}` for theorems, whereas this document still recommends the old notation <code>```{theorem}</code>, which is less good.
   - There is now a `fig.alt = ...` option to R chunks, which allows you to have a more detailed alt text (alongside the less detailed caption), which this document doesn't mention.

## Teaching development morning, 2021

I'm giving a talk at the teaaching development morning for the School of Mathematics and the University of Leeds on 14 December 2021.

* **[Slides for my talk](rmarkdown-slides.html)**
  * [R Markdown source code](https://github.com/mpaldridge/rmarkdown/blob/main/rmarkdown-slides.Rmd) for the above slides
  * Handout for the talk "knitted" from exactly the same code as built the slides themselves [[HTML format]](rmarkdown-handout.html) or [[PDF format]](rmarkdown-handout.pdf)

## Notes for students

This year, I have taught our first statistics module [MATH1710 Probability and Statistics I](https://mpaldridge.github.io/math1710), which is also the first place we teach our students about R. As part of the R training in that module I produced [**a worksheet on R Markdown** (HTML format)](https://mpaldridge.github.io/math1710/R6.html) [(Rmd format)](https://mpaldridge.github.io/math1710/R6.Rmd). 

## Useful references

- The "bibles":
  - [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)
  - [R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/)
  - [bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)
- [My guide to R Markdown and Bookdown](https://mpaldridge.github.io/rmarkdown-bookdown/) (a bit out of date)
- [Serguei Komissarov's guide to Bookdown](https://minerva.leeds.ac.uk/bbcswebdav/courses/201920_5685_MATH2620/BB-Guide/index.html)
- [Cosma Shalizi's guide to R Markdown](http://www.stat.cmu.edu/~cshalizi/rmarkdown/)

## My Bookdown lecture notes

My notes for the University of Leeds module MATH1710 Probability and Statistics I were written in R Markdown with the Bookdown package. (A few R Worksheets at the end are written in "plain" R Markdown without Bookdown.)

- [MATH1710 lecture notes](https://mpaldridge.github.io/math1710/index.html)
  - [Source code](https://github.com/mpaldridge/math1710) for those lecture notes

