R guides & galleries for data analysis & presentation
================

  - [Learn to analyse data with R](#learn-to-analyse-data-with-r)
  - [Learn to visualise data with R](#learn-to-visualise-data-with-r)
  - [Putting it all together](#putting-it-all-together)

These guides and galleries can help you master the key skills of data
analysis and presentation with R. I’ve put them together to help anyone
totally new to R (like I was not long ago). While I know a lot more now,
I still come back to all theses guides and galleries to learn more.

## Learn to analyse data with R

:one: **Learn data analysis in R from scratch:**

  - Learn how to analyse data using RStudio from zero knowledge to quite
    advanced by following [Modern R with the
    tidyverse](https://b-rodrigues.github.io/modern_R/).
  - Another popular guide is [R for Data
    Science](https://r4ds.had.co.nz). Another very comprehensive guide
    to R analysis from scratch is an [Introduction to Data
    Science](https://rafalab.github.io/dsbook/). Not all of the code is
    shown but it can be found [here](https://github.com/rafalab/dsbook)
    when needed.
  - A good set of lessons called [Programming wtih
    R](http://swcarpentry.github.io/r-novice-inflammation/) is aimed at
    non-programmers and teaches using a real data analysis task on one
    data set (learning by doing is best - see bullet 3 below).
  - Another good guide is [Practical Data Science with
    R](https://livebook.manning.com/#!/book/practical-data-science-with-r/about-this-book/).

:two: **Totally new to code or R? Scared you will fail and feel
stupid?:**

  - If you’ve never coded before, or you have struggled to improve your
    R skills, consider paying for gentle guided learning from DataCamp.
    Their [Data Analyst with R skill
    track](https://www.datacamp.com/tracks/data-analyst-with-r) takes
    you through 16 courses in a logical order. They assume no prior
    knowledge or skills.
  - A free alternative but for a more limited range of fundamental
    skills are the interactive [RStudio
    Primers](https://rstudio.cloud/learn/primers).

:three: **Don’t train too much. Do real analysis early:**

  - It can be tempting to complete many courses before you feel ready to
    try your own analysis. Instead, try writing your own simple analysis
    in R code as soon as you can, even if you don’t feel ready.
  - A good first project is replacing an Excel data task you know well
    with R code. Doing real things early is David Robinson’s philosophy
    he explains in the section titled [Get students doing powerful
    things early](http://varianceexplained.org/r/teach-tidyverse/).
  - Ideally, find a mentor to help you code your first projects. It’s a
    quicker way to learn.

:four: **Become an independent problem solver:**

  - Don’t hesitate to ask for help or to Google your problem or
    question. Getting better at solving your own problems using Google
    and other resources is an important skill to learn too, even when
    you have become an expert R programmer.
  - This [Getting Help in
    R](https://blog.rsquaredacademy.com/getting-help-in-r-updated/) blog
    tells you about the best places to find help. The more you look for
    help, the better you become at judging which web sites and people
    help you the most.

:five: **Write code in this clean style:**

  - Write clear code by following [The tidyverse style
    guide](https://style.tidyverse.org). It will be easier for you and
    others to Quality Assure.
  - You can also style your code automatically by running the [RStudio
    Styler add-in](http://styler.r-lib.org).

:six: **Repeating the same analysis regularly? Consider converting to an
R package:** \* If your data analysis is regularly repeated, consider
converting it into a [Reproducible Analytical Pipeline
(RAP)](https://ukgovdatascience.github.io/rap_companion/). \* Start to
learn how to build a RAP by building the most simple [R
Package](https://r-pkgs.org/index.html) possible first. However,
packages are a more advanced topic. \* You won’t need to build them if
you are just starting out.

:seven: **Use GitHub to save your code:**

  - Start saving your code on GitHub even when if you first start to
    learning R. This is called versioning your code.
  - However, GitHub can be hard to learn if you only use the text
    commands typed at the command prompt. An easier way to learn GitHub
    with RStudio is through the menus and buttons as explained in [Using
    git from RStudio
    tutorial](https://nceas.github.io/oss-lessons/version-control/4-getting-started-with-git-in-RStudio.html).
  - GitHub can also be fiddly to get working with RStudio. This is why
    Jenny Bryan has written [Happy Git and GitHub for the
    useR](https://happygitwithr.com/) to help her students troubleshoot
    the many potential problems. Because of these challenges with
    GitHub, ideally find an experienced user of RStudio and GitHub to
    coach you in person.

## Learn to visualise data with R

:eight: **Explore your data first (EDA):** Some R tools let you do
Exploratory Data Analysis (EDA) interactively with a [Point-and-Click
interface](https://en.wikipedia.org/wiki/Point_and_click). This can be
faster and easier than coding alone, particularly when you first start
to learn R. For example:

  - [esquisse](https://github.com/dreamRs/esquisse) is an RStudio
    “Addin” that launches the Point-and-Click interface shown below.
    Use it to build simple ggplot plots. The tool also automatically
    generates the code you need for each plot that you create with it.
    Even advanced R users can find ggplot code tricky so esquisse can be
    useful for everyone. Here is a long list of many more [RStudio
    Add-ins](https://github.com/daattali/addinslist) to try.

![](https://raw.githubusercontent.com/dreamRs/esquisse/master/man/figures/esquisse.gif)

  - [rpivotTable](https://cran.r-project.org/web/packages/rpivotTable/vignettes/rpivotTableIntroduction.html)
    is the R version of Excel’s Pivot Tables and Charts. It’s great for
    quickly exploring your data with heat maps, bar charts, line charts
    etc.. in an R Markdown html output document (R Markdown is described
    later).

![](https://raw.githubusercontent.com/nicolaskruchten/pivottable/master/images/animation.gif)

  - **Part-automate your EDA**: The blog post [Explore the landscape of
    R packages for automated data
    exploration](http://smarterpoland.pl/index.php/2019/04/explore-the-landscape-of-r-packages-for-automated-data-exploration/),
    its [detailed paper](https://arxiv.org/pdf/1904.02101.pdf), and
    associated
    [autoEDA-resources](https://github.com/mstaniak/autoEDA-resources)
    GitHub repository describe many automatic tools you can try. You can
    view several examples of the automatic EDA reports these tools can
    create
    [here](https://github.com/mstaniak/autoEDA-resources/tree/master/autoEDA-paper/plots).
    For example, here is a
    [DataExplorer](https://github.com/mstaniak/autoEDA-resources/blob/master/autoEDA-paper/plots/DataExplorer/dataexplorer_example.pdf)
    automatic report and this an example from
    [SmartEDA](https://github.com/mstaniak/autoEDA-resources/blob/master/autoEDA-paper/plots/SmartEDA/smarteda_report_target.pdf).
    Both are generated from just one line of code. DataExplorer and
    smartEDA automatic reports work best when you first: keep only
    relevant columns, choose the correct data type for each column (this
    could be done as you [read
    in](https://www.r-bloggers.com/using-colclasses-to-load-data-more-quickly-in-r/)
    the data), and you set one column as the response or outcome.

:nine: **Make Exploratory Data Analysis easy for yourself:**

  - In his chapter [Data exploration versus data
    presentation](https://serialmentor.com/dataviz/choosing-visualization-software.html#data-exploration-versus-data-presentation)
    Claus Wilke suggests using any tool that makes data exploration
    quick and easy for you.
  - As your R skills improve you will gradually use R code more to
    explore your data. For example, Roger Peng’s [Exploratory Data
    Analysis with R](https://bookdown.org/rdpeng/exdata/) clearly
    explains how to explore data using R code that is both easy to
    understand and run for yourself.

:one::zero: **Pick the right visualistion to tell your data story:** \*
Use this [Data to Viz](https://www.data-to-viz.com/) website to help you
pick the right visualisation for the type of data. \* Also, scan the
left hand contents panel of the [Fundamentals of Data
Visualisation](https://serialmentor.com/dataviz/) guide by Claus Wilke
to find the right visualisation for the point you are trying to make.
The charts in his book are written in R code that you can find in its
[GitHub repository](https://github.com/clauswilke/dataviz). \* However,
Wike didn’t write the book to teach R code skills. It is tool and
language neutral. Instead, learn how to create ggplot visualistions in R
code with the [R Graphics Cookbook](https://r-graphics.org/) from the
broader [Cookbook for R](http://www.cookbook-r.com).

:one::one: **Learn to build ggplots easily step-by-step:** \* If you are
just starting to use ggplot, learn intuitively how to build up the code
you need one line at a time with this [flipbook
guide](https://evamaerey.github.io/ggplot_flipbook/ggplot_flipbook_xaringan.html#1).
\* While [this
flipbook](https://evamaerey.github.io/tidyverse_in_action/tidyverse_in_action.html#1)
also includes some simple data preparation code before the plots are
built line by line. \* And one more from a [hands on
workshop](https://djnavarro.github.io/satrdayjoburg/slides/#1). \* Also,
Michael Toth’s [Detailed Guide to Plotting Line Graphs in R using ggplot
geom\_line](https://michaeltoth.me/a-detailed-guide-to-plotting-line-graphs-in-r-using-ggplot-geom_line.html)
helps you build an intuitive understanding of line plots in ggplot. His
blog post on [ggplot Scatter
plots](https://michaeltoth.me/a-detailed-guide-to-the-ggplot-scatter-plot-in-r.html#a-detailed-guide-to-the-ggplot-scatter-plot-in-r)
is good too.

:one::two: **Make your plots interactive:** \* From the [Gallery of
interactive R visualisations](http://gallery.htmlwidgets.org/) I
strongly recommend [Plotly](https://plot.ly/r/) for a huge variety of
easy to code interactive charts. And for easy to code time series charts
[dygraphs](http://rstudio.github.io/dygraphs/) is visually exciting. \*
Creating interactive plots also improves your data exploration. Carson
Sievert who maintains the Plotly R package demonstrates here how if
interactive plots are built quickly (as is possible with Plotly) they
can [augment your data
exploration](https://talks.cpsievert.me/20180202/#1).

:one::three: **Does a ggplot extension improve your story?:** With this
[gallery of ggplot extensions](https://www.ggplot2-exts.org/gallery/)
create a greater variety of ggplots that can improve the story you tell
in data. The most popular extension is gganimate described next.

:one::four: **Consider animating your plots:** \* If movement of data
points better explains the story you are telling, animate them with
[gganimate](https://github.com/billster45/gganimate-experiments/blob/master/README.md).
\* Learn how to [animate ggplots
intuitively](https://github.com/billster45/gganimate-experiments/blob/master/README.md)
using my guide inspired by a good Tweet.

![](images/gapminder.gif)

## Putting it all together

:one::five: **Be creative - but don’t break these rules\!** It is
surprisingly easy to build bad or ugly visualisations and not realise
how it could be better. Continually criticise your own plots. Ask others
to challenge your work. This Economist post called [Mistakes, we’ve
drawn a
few](https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368)
is a good example of effective criticism of your own data
visualisations. Use any of the following to challenge your own plots:

  - Use [The Office for National Satistics Data Visualisation
    guide](https://style.ons.gov.uk/category/data-visualisation/) to
    check your visualisation does not break any of their rules.

  - Similar to the ONS guide, here is good advice on avoiding [misleadig
    axes](https://callingbullshit.org/tools/tools_misleading_axes.html)
    and ensuring [“proportional
    ink”](https://callingbullshit.org/tools/tools_proportional_ink.html).

  - Find the type of visualisation you have made in the contents of
    Clause Wilke’s [Fundamentals of Data
    Visualisation](https://serialmentor.com/dataviz/) book. See if his
    advice for your type of plot can improve it.

![](images/plot2by2.png)

:one::six: **Present your final story:** \* Tell an engaging data story
in your final document. Claus Wilke’s chapter on [telling a story and
making a point](https://serialmentor.com/dataviz/telling-a-story.html)
shows you how to tell stories with engaging visuals that won’t confuse
your audience. \* On the Data Science competition website called Kaggle,
browse the [Kaggle
“kernels”](https://www.kaggle.com/kernels?sortBy=voteCount&group=everyone&pageSize=20&language=R)
in R with the most votes.There are many ideas here for powerful story
telling in data.

:one::seven: **Present your story with R Mardown:** \* One of the most
effective formats for story telling in data is [R
Markdown](https://rmarkdown.rstudio.com/gallery.html), particularly if
you create interactive html documents. \* Here is a [Quick
Tour](https://rmarkdown.rstudio.com/authoring_quick_tour.html). Browse
through the examples of others in [RPubs](https://rpubs.com/).

:one::eight: **Watch a master story teller use R:** Even with only basic
R skills you can learn a lot from watching an R expert rapidly explore
and visualise data to tell a story. David Robinson records himself
carrying out live data analysis in R using data he has never seen
before. In this recording he explores [wind turbine
locations](https://youtu.be/O1oDIQV6VKU) in the USA. It is one of the
many [TidyTuesday](https://github.com/rfordatascience/tidytuesday) data
sets he has coded live. Here is an RStudio competition winning Shiny app
that can show the most liked tweets for each data set:
[tidytuesday.rocks](https://nsgrantham.shinyapps.io/tidytuesdayrocks/)

:one::nine: **Telling good stories is hard because of the curse of
knowledge:** Aim to tell your data story to someone who doesn’t know
what you know about the data. But, it is surprisingly hard to remember
what it was like to **not** know what you now know, particularly after
spending so long exploring the data set. This amnesia about your prior
limited knowledge is called the [curse of
knowledge](https://en.wikipedia.org/wiki/The_Sense_of_Style#The_curse_of_knowledge).
To defeat this curse, assume as little knowledge as possible in your
final document. The more prior knowledge you assume, the more likely it
is your text, code and visualisations lose your audience. Or even worse,
you accidentally mislead them.

:two::zero: **Explain clearly. Democratise:** A clear plain style in
your writing, code and visualisations aimed at the widest audience
possible doesn’t have to be dumbed down or over simplified. You can
still present technical topics. For example, here I have tried to
explain [key Natural Language Processing
techniques](https://github.com/billster45/NLP-Intuition/blob/master/README.md)
in R while assuming no prior knowledge. Try not to be a gatekeeper of
your growing R knowledge and skills. Share, explain and democratise what
you know. You can then move on to more complex analysis in R with an
even higher value (as proposed by Richard Susskind in [The Future of
Professions](https://www.amazon.co.uk/dp/0198713398/)).
