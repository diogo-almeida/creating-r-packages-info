# Creating Packages in R. A personal guide.

**Diogo Almeida**

## Useful resources for learning how to create packages in R

* David Diez's [tutorial][DD1] and [slides][DD2].
* Hadley Wickham's [slides][HW1] and [R package programming web site][HW2].
* Jeff Allen's [slides][JA1].
* William Revelle's [tutorial][WR1].
* Friedrich Leisch's [official tutorial][FL1].
* Heng Weng's [slides][HWeng1]
* Using RStudio: [youtube video][yv-01], [online documentation][RS1]

[DD1]: http://rfunction.com/file/BuildingRPackagesPaper.pdf
[DD2]: http://www.hsph.harvard.edu/statinformatics/soft/files/buildingrpackages.pdf
[HW1]: http://scholarship.rice.edu/bitstream/handle/1911/36084/r-packages.key.pdf?sequence=2
[HW2]: http://r-pkgs.had.co.nz/
[JA1]: http://trestletechnology.net/wp-content/uploads/2013/06/reproducible_r.pdf
[WR1]: http://personality-project.org/r/makingpackages.html
[FL1]: http://cran.r-project.org/doc/contrib/Leisch-CreatingPackages.pdf
[HWeng1]: http://www.stt.msu.edu/~cui/Groupmeeting/R_package_tutorial.pdf
[yv-01]: http://www.youtube.com/watch?v=9PyQlbAEujY
[RS1]: https://support.rstudio.com/hc/en-us/articles/200486488-Developing-Packages-with-RStudio

# Useful resources for learning how to document packages in R using [Roxygen][]


* Roxygen's [documentation][Roxygen]
* [RStudio][]'s [documentation][RSdoc]
* [Danenberg & Eugster slides][http://roxygen.org/useR/roxygen-part-1.pdf]

[Roxygen]: http://cran.r-project.org/web/packages/roxygen2/roxygen2.pdf
[RStudio]: http://www.rstudio.com/
[RSdoc]:   http://www.rstudio.com/ide/docs/packages/documentation

## Issues with creating packages in R I have encountered

1. 

2. How do I document datasets using roxygen?

Found solution [here][1] and [here][2].

[1]: http://stackoverflow.com/questions/7086805/how-can-i-document-datasets-without-adding-them-to-the-collate-field
[2]: http://stackoverflow.com/questions/9561684/documenting-dataset-with-roxygen2

3. Package wouldn't check out because pdflatex wasn't in the R path. _(10/30/13)_

Found solution [here][3] and [here][4]. Created the _.Rprofile_ solution given on the second link.

[3]: http://www.r-bloggers.com/building-r-packages-missing-path-to-pdflatex/
[4]: http://kmyu.wordpress.com/2011/01/29/binsh-latex-command-not-found-setting-r-path-to-include-tex-binaries-path/

4. How can I load the datasets from the package such that the examples work when checking the package _(10/30/13)_

Found solution [here][5] and [here][6].

[5]: http://stackoverflow.com/questions/11772156/exporting-data-in-roxygen2-so-that-they-are-available-without-requiring-data/
[6]: http://stackoverflow.com/questions/8898469/is-it-possible-to-use-r-package-data-in-testthat-tests-or-run-examples

5. How to properly use Template Tags? _(10/30/13)_

Found solutions [here][7].

[7]: http://stackoverflow.com/questions/15100129/using-roxygen2-template-tags

## Still need to learn

* How to use package [devtools][].

    Useful resources:
        - [DevTools in RStudio][devtools-rs]


[devtools]: http://cran.r-project.org/web/packages/devtools/devtools.pdf
[devtools-rs]: http://www.rstudio.com/products/rpackages/devtools/
* How to use package [testthat][]

    Useful resources:
        - [RJournal][testthat-rj]
        - [Github source][testthat-gh]

[testthat]: http://cran.r-project.org/web/packages/testthat/testthat.pdf
[testthat-rj]: http://journal.r-project.org/archive/2011-1/RJournal_2011-1_Wickham.pdf
[testthat-gh]: https://github.com/hadley/testthat

* How to use package [roxyPackage][], which looks pretty awsome.

[roxyPackage]: http://lamages.blogspot.com/2013/03/create-r-package-from-single-r-file.html



