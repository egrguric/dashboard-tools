---
layout: default
title: R packages
parent: Introduction
nav_order: 6
---
# About R
R is a heavily Statistics focused programming language and is particularly common when statistical analysis is a core element of your work. Originally built with statisticians in mind, R does very well for visualising statistical concepts. It is a procedural language and may have a lower onboarding curve for some beginners who have less experience with programming because of RStudio, a relatively intiutive tool for working with R.

## Visualization packages
* [ggplot2](https://ggplot2.tidyverse.org/) - grammar of graphics
  * Not for higher complexity; best for smaller
  * Grammar of Graphics breaks data visualization into semantic concepts
  * Think of this as “layering” parts of a visualization
  * This is one of the most popular R packages and was intended as a replacement for defaults included in R
  * ggplot2 allows users to be modular in how they chart and how they load information into a chart. What this means is that you can adjust at a high level of granularity.
* [patchwork](https://patchwork.data-imaginist.com/) - presenting ggplot2 charts next to each other
  * Literally a tool for patching them together nicely
* [ggiraph](https://davidgohel.github.io/ggiraph/)
  * Adds dynamic components onto ggplot2 graphs
  * Tooltips, javascript actions on click, and a way to reference a specific element of the plot
  * Allows export to SVG as well, just extends ggplot2 and htmlwidgets
* [Plotly](https://plotly.com/r/)
  * Plot.ly is essentially an online version of ggplot2 and has since become an open source tool that can be used through R, Python, and Julia
  * It’s incredibly powerful and has chart types that are not necessarily available to you elsewhere
  * Has a relatively new component called “dash” for creating dashboards, generally references as more of a Python tool but can be used with R and Julia as well
* [htmlwidgets](https://www.htmlwidgets.org/)
  * A way to use JavaScript visualization libraries at the R console, without needing to know Javascript -- an example of a useful JS lib you are likely to hear about is D3.js
  * You can embed widgets in R Markdown documents and Shiny web applications
  * Can handle larger datasets depending on how you’re using it
* [dygraphs](https://dygraphs.com/)
  * Also brings javascript into R
  * Core benefits of dygraphs is that it is designed with very large datasets in mind and is interactive out of the box
  * For instance some forms of interactivity are added on to packages like ggplot2 but in this case they’re built in

While we aren't going into maps in this session a few packages to be aware of:
* [mapboxr](https://cran.r-project.org/web/packages/mapboxer/vignettes/mapboxer.html) - MapBox in R
* [leaflet](https://rstudio.github.io/leaflet/) - package for working with leaflet.js in R
* [geofacet](https://cran.r-project.org/web/packages/geofacet/vignettes/geofacet.html) - extends ggplot2 to work with geodata

## Bringing it all together into a dashboard
* [flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/)
  * Can be used with RMarkdown or Shiny

* [RMarkdown](https://rmarkdown.rstudio.com/)
  * RMarkdown can be a component of a lot of different things, very flexible
  * RNotebooks - more interactive RMarkdown files and by default possible with all RMarkdown files created via RStudio
  * [Example RMarkdown dashboards](https://bookdown.org/yihui/rmarkdown/dashboards.html)

* [RShiny](https://shiny.rstudio.com/)
  * Robust web framework for developing apps, not just dashboards
  * Relatively easy and intuitive compared to other alternatives because it includes more structural elements and styling out of the box; can be a bit harder to customize as a result
  * While very large apps can be a bit laggy but RShiny is best when working with data that you can't fully expose or need to store in a database
  * [Example RShiny Apps](https://demo.appsilon.ai/)

## A note about working with R
While you can work with R in a number of ways the most common tool is RStudio which is a robust multi-purpose programming environment built around R.

[RStudio](https://rstudio.com/products/rstudio/)
* Open Source edition is free for local access
* Many features for workflow management

[RStudio Server](https://rstudio.com/products/rstudio/)
* Allows you to edit in the cloud which can save on RAM.

You can also use [RStudio in the cloud](https://login.rstudio.cloud) for free for smaller tasks.
