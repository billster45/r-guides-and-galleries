R guides & galleries for data analysis & presentation
================

-   [Learn to analyse data with R](#learn-to-analyse-data-with-r)
-   [Learn to visualise data with R](#learn-to-visualise-data-with-r)
-   [Putting it all together](#putting-it-all-together)

A short list of **core** R guides and galleries.

Following these can lead you from zero experience to mastering the key skills of data analysis and presentation with R.

Learn to analyse data with R
----------------------------

1.  **Learn R Code Skills:** Learn RStudio and R code from zero knowledge to quite advanced using [Modern R with the tidyverse](https://b-rodrigues.github.io/modern_R/). Another popular guide to use alongside is [R for Data Science](https://r4ds.had.co.nz).

2.  **Totally new to code or R? Scared you will fail and feel stupid?:** If you've never coded before, or you haven't progressed quickly with other R training materials our courses, consider paying to access the very gentle guided learning content created by DataCamp. This [data analyst skill track](https://www.datacamp.com/tracks/data-analyst-with-r) contains 16 courses to take in a logical order. They require no pre-exiting knowledge or skills.

3.  **Don't train too much. Do real analysis early:** But with guided learning like DataCamp it can be tempting to complete many courses before you feel ready to try your own analysis. Instead, try doing real simple tasks in R code as soon as you can even if you don't feel ready. Replacing an Excel task you know well with R code is often a good first project. Ideally get support from a mentor to help you do that. It's quicker. Doing real things early is David Robinson's philosphoy. He explains it well in the section titled [Get students doing powerful things early](http://varianceexplained.org/r/teach-tidyverse/).

4.  **Seek help often to become an independent problem solver:** Don't hesitate to ask for people for help or look online. Getting better at solving your own problems in R using Google and other resources is a really important skill to learn too, even when you're an expert R programmer. This [getting help in R](https://blog.rsquaredacademy.com/getting-help-in-r-updated/) blog summaries the main places to find help. The more you seek help the better you get at judging which web sites and people help you quickly with good solutions.

5.  **Code Style:** Write clear code that is easier to Quality Assure by following [The tidyverse style guide](https://style.tidyverse.org). Though it's much less effort to style your code automatically by running the [RStudio Styler add-in](http://styler.r-lib.org).

6.  **Package Code:** If your data analysis is regularly repeated or re-used, consider converting it into a [Reproducible Analytical Pipeline (RAP)](https://ukgovdatascience.github.io/rap_companion/). Start to learn how to build a RAP by learning how to build the most simple [R Package](https://r-pkgs.org/index.html) possible first.

Learn to visualise data with R
------------------------------

1.  **Explore your data first:** There are several R tools let you explore your data interactively faster and easier than coding alone. For example:

[esquisse](https://github.com/dreamRs/esquisse) is an RStudio "Addin" that launches a Point-and-Click dialog which you use to interactively build simple ggplot plots and automatically generate the code for each plot you create. Even advanced R users can find ggplot code tricky so esquisse is useful for everyone. Here is a long list of many more [RStudio Add-ins](https://github.com/daattali/addinslist).

<img src="https://raw.githubusercontent.com/dreamRs/esquisse/master/man/figures/esquisse.gif" style="width:70.0%" />

[rpivotTable](https://cran.r-project.org/web/packages/rpivotTable/vignettes/rpivotTableIntroduction.html) is the R version of Excel's Pivot Tables and Charts. It's great for quickly exploring your data with heat maps, bar charts, line charts etc. in an R Markdown html output document.

<img src="https://raw.githubusercontent.com/nicolaskruchten/pivottable/master/images/animation.gif" style="width:70.0%" />

1.  **Pick the right visualistion to tell your data story:** Follow the [Fundamentals of Data Visualisation](https://serialmentor.com/dataviz/) guide by Claus Wilke to pick the right visualisation for the point you are trying to make. The chapter on [telling a story and making a point](https://serialmentor.com/dataviz/telling-a-story.html) is particularly good about the importance of story telling in data. While the charts in Wilke's book are written in R code that you can find in its [GitHub repository](https://github.com/clauswilke/dataviz), it does not aim to teach R code data visualistion skills. For a quick guide on how to create visualistions in R code the [graphs chapter](http://www.cookbook-r.com/Graphs/) in the [Cookbook for R](http://www.cookbook-r.com) is more helpful.

2.  **Learn to build ggplots easily step-by-step:** If you are just starting to use ggplot, learn more intuitively how to build up the code you need line-by-line with this [flipbook guide](https://evamaerey.github.io/ggplot_flipbook/ggplot_flipbook_xaringan.html#1). While [this flipbook](https://evamaerey.github.io/tidyverse_in_action/tidyverse_in_action.html#1) also includes some simple data preparation examples before building the charts step-by-step.

3.  **Make your plots interactive:** [Gallery of interactive R visualisations](http://gallery.htmlwidgets.org/). From this gallery, I strongly recommend trying the [dygraphs](http://rstudio.github.io/dygraphs/) package for time series charts, use [Plotly](https://plot.ly/r/) for a huge variety of easy to code interactive charts.

4.  **See if a ggplot extension helps your story:** This [gallery of ggplot extensions](https://www.ggplot2-exts.org/gallery/) lets you create a greater variety of different plots that may better support your narrative.

5.  **Consider animating your plots:** If movement of data points in your plot will help better explain the story you are telling, animate it with [gganimate](https://github.com/billster45/gganimate-experiments/blob/master/README.md). Learn how to [animate ggplots intuitively](https://github.com/billster45/gganimate-experiments/blob/master/README.md) using my guide inspired by a good Twitter post.

<img src="images/gapminder.gif" style="width:70.0%" />

Putting it all together
-----------------------

1.  **Watch a master at work:** Even when you only have basic R code skills you will still benefit from watching how well an R expert rapidly explores and visualises data. David Robinson records live R coding videos in one hour on data he has never seen before. Here is a good example that explores [wind turbine locations](https://youtu.be/O1oDIQV6VKU) in the USA. It is one of the many [TidyTuesday](https://github.com/rfordatascience/tidytuesday) data sets he has coded live with you can search for on YouTube.

2.  **Be creative, but follow the rules!:** While data visualisation allows creativity, exploration and personal expression, it is surprisingly easy to build bad or ugly visualisations. You must continually criticise your own plots, and ask others to challenge your work. Use the rules in [The Office for National Satistics Data Visualisation guide](https://style.ons.gov.uk/category/data-visualisation/) to challenge your visualisations and then improve them. You can also find your visualisation type in Clause Wilke's [Fundamentals of Data Visualisation](https://serialmentor.com/dataviz/) book and see how his advice can improve your plot. This Medium post from The Economist called [Mistakes, we've drawn a few](https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368) is a good example of effective self-criticism.

<img src="images/plot2by2.png" style="width:100.0%" />

1.  **Present your final story:** Your final story in a document of some kind (e.g. web page, Word or PowerPoint) is where you tell your engaging story. But often, you have spent so long with your data you will suffer from the [curse of knowledge](https://en.wikipedia.org/wiki/The_Sense_of_Style#The_curse_of_knowledge). You can no longer remember what it is like **not** to know what you now know. Assume as little knowledge as possible in your final document to defeat this curse. T

2.  **Widen your auidence. Democratise:** Defeating the curse of kowledge is hard. Unless you assume no prior knowledge, your writing, code and visualisations can turn off much far more of your audience than you realise. Or worse, mislead them. This style is not the same as dumbing down or over simplyifying. You can still present technical topics in this way. For example, here I have tried to explain [key Natural Language Processing techniques](https://github.com/billster45/NLP-Intuition/blob/master/README.md) in R code and data while assuming no prior technical knowledge. May aim is to help readers reach a satisfying and intuitive understanding. Don't be a gatekeeper of your knowledge and skills. It is better to democratise what you know while you move on to more complex work with a higher value (as proposed by Richard Susskind in [The Future of Professionns](https://www.amazon.co.uk/dp/0198713398/))
