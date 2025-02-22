---
title: "Annotations"
linktitle: "9: Annotations"
date: "2022-07-11"
due_date: "2022-07-11"
due_time: "11:59 PM"
toc: true
menu:
  assignment:
    parent: Exercises
    weight: 9
type: docs
editor_options: 
  chunk_output_type: console
---

## Getting started

For this exercise, you'll use whatever data you want to make a plot and add annotations to it. Use a dataset from a past exercise, use one of the built-in datasets like `mpg` or `gapminder` from the **gapminder** package, download stuff from the World Bank using the **WDI** package, or use something from [this list of datasets](/resource/data/).

You should use an RStudio Project to keep your files well organized (either on your computer or on RStudio.cloud). Either create a new project for this exercise only, or make a project for all your work in this class.

**To help you**, I've created a skeleton R Markdown file with a template for this exercise, along with some code to help you clean and summarize the data. Download that here and include it in your project:

- [<i class="fab fa-r-project"></i> `09-exercise.Rmd`](/projects/09-exercise/09-exercise.Rmd)

In the end, the structure of your project directory should look something like this:

```text
your-project-name\
  09-exercise.Rmd
  your-project-name.Rproj
  data\
    WHATEVER.csv
```

To check that you put everything in the right places, you can download and unzip this file, which contains everything in the correct structure:

- [<i class="fas fa-file-archive"></i> `09-exercise.zip`](/projects/09-exercise.zip)

The [documentation for `annotate()`](https://ggplot2.tidyverse.org/reference/annotate.html), [`geom_text()` and `geom_label()`](https://ggplot2.tidyverse.org/reference/geom_text.html), and [`geom_text_repel()` and `geom_label_repel()`](https://cran.r-project.org/web/packages/ggrepel/vignettes/ggrepel.html) will be incredibly helpful for this exercise. [The example for today's session](/example/09-example/) is also helpful for seeing annotations in real life.

Again, you don't need to make your plots super fancy (except for these annotations), but if you're feeling brave, experiment with changing colors or modifying themes and theme elements.

You'll need to insert your own code chunks where needed. Rather than typing them by hand (that's tedious and you might miscount the number of backticks!), use the "Insert" button at the top of the editing window, or type <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>i</kbd> on Windows, or <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>i</kbd> on macOS.

<img src="../../../../../../../img/assignments/insert-chunk-button.png" width="19%" />

## Task 1: Reflection

Write your reflection for the day's readings.


## Task 2: Annotations

Do the following:

1. Make a plot. Any kind of plot will do (though it might be easiest to work with `geom_point()`).

2. Label (some or all of) the points using one of `geom_text()`, `geom_label()`, `geom_text_repel()`, or `geom_label_repel()`. You might need to make a new indicator variable so that you only highlight a few of the points instead of all of them. [See this slide for an example](hslides/09-slides.html#29), as well as [the complete example plot on the example page](/example/09-example/) for today's session.

3. Add *at least two each** the following annotations somewhere on the plot using `annotate()`:

    - **Text**
    - **An arrow** (look at [this page](https://www.r-graph-gallery.com/233-add-annotations-on-ggplot2-chart.html), or search for "arrow" [on this page](https://ggplot2-book.org/annotations.html) for examples). Make a curved arrow for bonus fun.
    - **A rectangle**
    
    You can add more if you want, but those three are the minimum. Try to incorporate the annotations into the design of the plot rather than just placing them wherever.


## Turning everything in

When you're all done, click on the "Knit" button at the top of the editing window and create an HTML or Word version (or PDF if you've [installed **tinytex**](/resource/install/#install-tinytex)) of your document. Upload that file to iCollege.

<img src="../../../../../../../img/assignments/knit-button.png" width="30%" />
