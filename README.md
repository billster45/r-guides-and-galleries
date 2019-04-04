R guides & galleries for data analysis & presentation
================

-   [Learn to analyse data with R](#learn-to-analyse-data-with-r)
-   [Learn to visualise data with R](#learn-to-visualise-data-with-r)

A short list of **core** R guides and galleries.

Following these can lead you from zero experience to mastering the key skills of data analysis and presentation with R.

Learn to analyse data with R
----------------------------

1.  **Code Skills:** Learn RStudio and R code from zero knowledge to quite advanced using [Modern R with the tidyverse](https://b-rodrigues.github.io/modern_R/).

2.  **Seek help often - become independent:** Don't hesitate to ask for people for help or look online. Getting better at solving your own problems in R using Google and other resources is a really important skill to learn too, even when you're an expert R programmer. This [getting help in R](https://blog.rsquaredacademy.com/getting-help-in-r-updated/) blog summaries the main places to find help. The more you seek help the better you get at judging which web sites and people help you quickly with good solutions.

3.  **Code Style:** Write clear code that is easier to Quality Assure by following [The tidyverse style guide](https://style.tidyverse.org). Though it's much less effort to style your code automatically by running the [RStudio Styler add-in](http://styler.r-lib.org).

4.  **Package Code:** If your data analysis is regularly repeated or re-used, consider converting it into a [Reproducible Analytical Pipeline (RAP)](https://ukgovdatascience.github.io/rap_companion/). Start to learn how to build a RAP by learning how to build the most simple [R Package](https://r-pkgs.org/index.html) possible first.

Learn to visualise data with R
------------------------------

1.  **Explore your data first:** There are several R tools let you explore your data interactively faster and easier than coding alone. For example:
    1.  [esquisse](https://github.com/dreamRs/esquisse) is an RStudio "Addin" that launches a Point-and-Click dialog which you use to interactively build simple ggplot plots and automatically generate the code for each plot you create. Even advanced R users can find ggplot code tricky so esquisse is useful for everyone. Here is a long list of many more [RStudio Add-ins](https://github.com/daattali/addinslist).
    2.  [rpivotTable](https://cran.r-project.org/web/packages/rpivotTable/vignettes/rpivotTableIntroduction.html) is the R version of Excel's Pivot Tables and Charts. It's great for quickly exploring your data with heatmaps, bar charts, line charts etc. in an R Markdown html output document.
    3.  [Trelliscopejs](https://ryanhafen.com/blog/trelliscopejs/) automatically plots your data into [small multiple plots](https://hafen.github.io/trelliscopejs/#why_small_multiples) (also known as facets), for each value of one or more data fields (e.g. every month in a year). This can be an efficient knowledge discovery technique for your data.
2.  **Pick the right visualistion to tell your data story:** Follow this [guide to the right visualisation for the task](https://serialmentor.com/dataviz/), particularly the chapter on [telling a story and making a point](https://serialmentor.com/dataviz/telling-a-story.html).

3.  **Learn to build ggplots easily step-by-step:** Learn now to build ggplot charts step-by-step with this [flipbook guide](https://evamaerey.github.io/ggplot_flipbook/ggplot_flipbook_xaringan.html#1). While [this version](https://evamaerey.github.io/tidyverse_in_action/tidyverse_in_action.html#1) also includes some simple data preparation examples before building the charts step-by-step.

4.  **Make your plots interactive:** [Gallery of interactive R visualisations](http://gallery.htmlwidgets.org/). From this gallery, I strongly recommend trying the [dygraphs](http://rstudio.github.io/dygraphs/) package for time series charts, use [Plotly](https://plot.ly/r/) for a huge variety of easy to code interactive charts, and [echarts4r](https://echarts4r.john-coene.com) is easy to code graphs that also include animation.

5.  **See if a ggplot extension helps your story:** This [gallery of ggplot extensions](https://www.ggplot2-exts.org/gallery/) lets you create a greater variety of different plots that may better support your narrative.

6.  **Consider animating your plots:** If movment of data points in your plot will help better explain the story you are telling, animate it with [gganimate](https://github.com/billster45/gganimate-experiments/blob/master/README.md).

7.  **Putting it all together:** Even when you only have basic R code skills you can benefit from watching how well an R expert can rapidly explore and visualise data. David Robinson records live R coding videos in one hour on data he has never seen before. Here is a good example that explores [wind turbine locations](https://youtu.be/O1oDIQV6VKU) in the USA. It is one of the many [TidyTuesday](https://github.com/rfordatascience/tidytuesday) data sets he has coded live with you can search for on YouTube.
