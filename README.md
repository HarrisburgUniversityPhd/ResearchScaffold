# Research Scaffold

This provides a [GitHub][github] repo format to help in research.

Download the repo (which encompasses all the files on this site) by clicking the `Clone or Download` button and select `Download ZIP`.
This will download a ZIP file of the entire site on your local computer.
Unzip the folder.

To use the scaffolding you will also need to have the following installed on your computer (instructions to follow):

1. [RStudio][rstudio]
2. A LaTeX Distribution like [TeXLive](https://www.tug.org/texlive) or [MikTeX](https://miktex.org)
3. Fonts used in the template [1](https://github.com/georgd/EB-Garamond),[2](https://github.com/adobe-fonts/source-code-pro),[3](http://www.latofonts.com/lato-free-fonts)
4. A few R packages [1](https://CRAN.R-project.org/package=bookdown),[2](https://CRAN.R-project.org/package=devtools),[3](https://CRAN.R-project.org/package=dplyr),[4](https://CRAN.R-project.org/package=ggplot2),[5](https://CRAN.R-project.org/package=kableExtra),[6](https://CRAN.R-project.org/package=knitr),[7](https://CRAN.R-project.org/package=readr)

## Understanding the scaffolding

A presentation that covers the intent of the scaffolding can be found in `./presentation/index.rmd`

## Using the scaffolding

Once you have everything installed, you can try compiling the default paper included in the template.
To do this, double click on `./paper/index.Rmd`, then press the "Knit" button.
The scaffolding paper is then compiled into a TeX document (`zzz_paper_zzz.tex`) and a PDF file (`zzz_paper_zzz.pdf`).
If the PDF of the scaffolding paper successfully compiles, congratulations!
You are ready to begin writing and adding your own content into the paper.

ToDo:

- [ ] Make subtitle link correctly

## Credits, Notes, and Thanks

This scaffold draws inspiration from several places.
This list is likely incomplete, but attempts to credit those that came before.

> "If I have seen further, it is because I stand on the shoulders of giants."

* [Andrew Zieffler](https://ccaps.umn.edu/andrew-zieffler) [github](https://github.com/zief0002/predissertation-paper) for forming the basis of paper section
* [Michael Ekstrand](https://md.ekstrandom.net/resources/umn-thesis/) [github](https://github.com/mdekstrand/umn-thesis)] for his inspired use of the `memoir` class to format scholarly work, the University of Minnesota thesis in particular.
* [Ben Marwick](https://github.com/benmarwick/huskydown/blob/master/README.md) for his work on `huskydown` (a thesis template for the University of Washington), especially the font choice. 
* [Yihui Xie](https://bookdown.org/yihui/bookdown/) for his work on `bookdown`, the work-horse beneath the template.
* [RStudio Team][rstudio] for their vision in creating RStudio, their continued resources in building educational resources, and their willingness to share all of it with the world.


## License

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <span rel="dct:publisher" resource="[_:publisher]">the person who associated CC0</span>
  with this work has waived all copyright and related or neighboring
  rights to this work.
</p>

[github]: https://github.com
[rstudio]: https://www.rstudio.com
