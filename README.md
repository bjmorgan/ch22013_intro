# CH22013: Introduction to Computational Chemistry

Lecture notes for the introductory lecture of CH22013 (Computational Chemistry) at the University of Bath.

## View Online

The compiled book is available at: https://bjmorgan.github.io/ch22013-intro/

## Building Locally

This project uses [bookdown](https://bookdown.org/) to generate the lecture notes.

### Requirements

- R (>= 4.0)
- bookdown package
- rmarkdown package

### Build

From R:

```r
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

Or from the command line:

```bash
Rscript -e 'bookdown::render_book("index.Rmd")'
```

The output will be in the `_book/` directory.

## License

This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).
