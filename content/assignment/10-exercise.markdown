---
title: "Interactivity"
linktitle: "10: Interactivity"
date: "2022-07-11"
due_date: "2022-07-11"
due_time: "11:59 PM"
toc: true
menu:
  assignment:
    parent: Exercises
    weight: 10
type: docs
editor_options: 
  chunk_output_type: console
---

This exercise is a little different from past ones because you will not knit to PDF or Word. *Pay attention to the instructions below.*


## Getting started

For this exercise, you'll use whatever data you want to create an interactive HTML plot and a dashboard. Use a dataset from a past exercise, use one of the built-in datasets like `mpg` or `gapminder` from the **gapminder** package, download stuff from the World Bank using the **WDI** package, or use something from [this list of datasets](/resource/data/).

You should use an RStudio Project to keep your files well organized (either on your computer or on RStudio.cloud). Either create a new project for this exercise only, or make a project for all your work in this class.

**To help you**, I've created a skeleton R Markdown file with a template for this exercise, along with some code to help you clean and summarize the data. Download that here and include it in your project:

- [<i class="fab fa-r-project"></i> `10-exercise.Rmd`](/projects/10-exercise/10-exercise.Rmd)

In the end, the structure of your project directory should look something like this:

```text
your-project-name\
  10-exercise.Rmd
  your-project-name.Rproj
  data\
    WHATEVER.csv
```

To check that you put everything in the right places, you can download and unzip this file, which contains everything in the correct structure:

- [<i class="fas fa-file-archive"></i> `10-exercise.zip`](/projects/10-exercise.zip)

[The example for today's session](/example/10-example/) will be helpful as you tinker with `ggplotly()`, and [the resources listed at the bottom of the example](/example/10-example/#making-a-dashboard-with-flexdashboard) will be helpful for making a dashboard.

You'll need to insert your own code chunks where needed. Rather than typing them by hand (that's tedious and you might miscount the number of backticks!), use the "Insert" button at the top of the editing window, or type <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>i</kbd> on Windows, or <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>i</kbd> on macOS.

<img src="../../../../../../../img/assignments/insert-chunk-button.png" width="19%" />

## Task 1: Reflection

Write your reflection for the day's readings.


## Task 2: Interactive plots

In the R Markdown file with your reflection, create an interactive plot with `ggplotly()` from the **plotly** package. Modify the tooltip to show something more useful than every single mapped aesthetic.


## Task 3: Dashboard

Install the **flexdashboard** package and create a new R Markdown file in your project by going to File > New File… > R Markdown… > From Template > Flexdashboard.

Using the documentation for **flexdashboard** online, create a super basic dashboard that shows a plot (static or interactive) in at least two chart areas. Play with the layout if you're feeling brave.


## Turning everything in

*Here's where this is all different this time.* You will *not* upload a knitted PDF or Word file to iCollege, since those can't handle interactivity. Instead, do this:

1. Knit the document with Tasks 1 and 2 in it to HTML and publish it to RPubs using the "Publish document" menu in the preview of the knitted file. Take note of the URL.

    <img src="../../../../../../../slides/img/10/publish-document.png" width="30%" />

2. Knit the dashboard from Task 3 to HTML and publish it to RPubs using the same menu. Take note of the URL.

3. In iCollege, paste the two URLs into the submission form for exercise 10 following this template:

    ```text
    Task 1 and 2: URL HERE
    Task 3 dashboard: URL HERE
    ```
