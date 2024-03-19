# EMA Cognition Research Lifecycle: Hosted by the CASCADE Lab
## A 3-day Workshop

  - ***Author:*** Nelson Roque, PhD
  - [nur375@psu.edu](nur375@psu.edu)
  - Director of the CASCADE Lab at Penn State.

-----

## Intentions of this Workshop

  - To train the next-generation of scientists to work with data - regardless of the type, format, or volume.
  - Make available a set of open-source materials to learn how to engage in reproducible science, leveraging code-based techniques.
  - This repository is intended to house various sample workflows, and code snippets, to support research + data science activities.

-----

## Background

***Workshop Overview:*** This workshop is designed to provide a comprehensive overview and practical skills in the application of Ecological Momentary Assessment (EMA) within cognition research. EMA is a valuable research tool that captures real-time data on individuals' cognitive states and processes in their natural environments. This workshop will guide participants through the lifecycle of an EMA cognition research project, from conceptualization to data analysis and dissemination of findings. Our aim is to empower researchers with the knowledge and tools necessary to effectively implement EMA methodologies in their work, enhancing the ecological validity and impact of their research on cognition.

## Workshop Format

  - ***Location***: In person at Penn State
  - ***Format***: Live
  - ***Register***: Registration closed.
  - ***Materials***: 
    - Data: see [`data`](data) folder of this repository.
    - Slides: see [`slides`](slides) folder of this repository.
    - Code: see [`scripts`](scripts) folder of this repository.
    - Textbook: [Click here for a web-based textbook to accompany this workshop](https://nelsonroque.github.io/contextlab_introdatascience_webcourse/index.html)

## Before the Workshop

  1. Install R
    - [Download R](https://cran.r-project.org/)
  2. Install RStudio
    - [Download RStudio](https://www.rstudio.com/products/rstudio/download/)
  3. Install packages for various analyses

    ```
    install.packages(c('tidyverse', 'devtools', 'readr', 'tidytext', 'textdata',
    'topicmodels', 'wordcloud', 'ggwordcloud'))
    ```

## Learning Objectives

  - Describe various tools and techniques supportive of open and reproducible science.
  - List and describe the FAIR Principles (https://www.go-fair.org/fair-principles)
  - Develop a code-only pipeline to allow reproducibility of data prep and analyses.
  - Develop a long-term learning plan for practicing reproducible science tools and techniques.

## Workshop Schedule

TODO: revise this!!! match word doc
  - ***Day 1 | July 6, 2022***
    - What is Reproducible Science?
    - Reproducible & FAIR Data Workflows
    - Tools Supporting Reproducible Science
    - Overview of available tools
      - Skill 1: Using Endnote for Reference Management
      - Skill 2: Using Git (and Github) for code management and collaboration
    - Orientation to R, RStudio, RMarkdown
      - Skill 3: R syntax primer
    - Data Science: Latest trends
    - Long-term Learning Recommendations
  - ***Day 2 | July 8th, 2022***
    - Data wrangling and visualization of Big Data
      - Skill 1: Data wrangling the Google Mobility dataset
    - Reproducible survey research
      - Qualtrics survey design tips
      - Skill 2:  Data wrangling Qualtrics data
    - Working with JSON data
      - Skill 3: cleaning and visualizing keystroke JSON data
  - ***Day 3 | July 11th, 2022***
    - Text mining
      - Skill 1: word and bigram frequency analysis
      - Skill 2: generating wordclouds
      - Skill 3: sentiment analysis
    - Interacting with APIs and JSON data
      - Skill 4: querying API for results and data aggregation
    - Closing Discussion & Q/A

## Submit your questions

Do you have any questions about the workshop or related content? [Submit your questions here](nur375@psu.edu)

## Resources

### Books

  - [R for Data Science](https://r4ds.had.co.nz/)
  - [Advanced R](https://adv-r.hadley.nz/index.html)
  - [R Graphics Cookbook](http://www.cookbook-r.com/)
  - [Text Mining with R](https://www.tidytextmining.com/)
  - [Reproducible Analyses with R](https://nceas.github.io/sasap-training/materials/reproducible_research_in_r_fairbanks/)
  - [Featured Bookdown books](https://bookdown.org/)

### Cheatsheets

  - [List of Cheatsheets](https://www.rstudio.com/resources/cheatsheets/)
  - [ggplot2](https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-visualization.pdf)
  - [dplyr](https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-transformation.pdf)
  - [tidyr](https://raw.githubusercontent.com/rstudio/cheatsheets/main/tidyr.pdf)
  - [Data import with readr, readxl, and googlesheets4 cheatsheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-import.pdf)
  - [Apply functions with purrr](https://raw.githubusercontent.com/rstudio/cheatsheets/main/purrr.pdf)
  - [String manipulation](https://raw.githubusercontent.com/rstudio/cheatsheets/main/strings.pdf)
  - [Working with dates and times](https://raw.githubusercontent.com/rstudio/cheatsheets/main/lubridate.pdf)
  - [RMarkdown](https://raw.githubusercontent.com/rstudio/cheatsheets/main/rmarkdown.pdf)

### Visualization

  - [R-Charts](https://r-charts.com/)
  - [Design your own Grid Plot](https://cran.r-project.org/web/packages/cowplot/vignettes/introduction.html)
  
### Stats
  - [Intro to R Stats](https://www.cyclismo.org/tutorial/R/)
  - [Multilevel Modeling Primer 1](https://quantdev.ssri.psu.edu/tutorials/r-bootcamp-introduction-multilevel-model-and-interactions)
  - [Multilevel modeling Primer 2](https://rpubs.com/rslbliss/r_mlm_ws)

### Blogs

  - [Revolution Analytics](https://blog.revolutionanalytics.com/)
  - [RBloggers](https://www.r-bloggers.com/)

### Interactive Learning Tools
  - [Swirl - Interactive R](https://swirlstats.com/)
  - [DataCamp](https://www.datacamp.com/courses/free-introduction-to-r)
  - [CodeAcademy](https://www.codecademy.com/catalog/language/r)