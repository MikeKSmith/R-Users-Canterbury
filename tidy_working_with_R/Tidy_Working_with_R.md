Tidy Working with R
========================================================
author: Mike K Smith
date: January 2018
autosize: true

Does this sound familiar?
========================================================

- You get data
- You push and pull data into shape for analysis
or visualisation
- You create analysis (formulas), graphs, tables
- You write a report

Does this sound familiar? - Scenario 1
========================================================

- Late breaking changes to the data
- PANIC!
- Recreate graphs, tables, report
- HAVE YOU CHANGED EVERYTHING?
- PANIC PANIC!

Does this sound familiar? - Scenario 2
========================================================

- You get the next set of data (like dataset 1)
- You push and pull data into shape for analysis (AGAIN!)
- You recreate formulae, graphs, tables (AGAIN!)
- You write (ANOTHER!) report that is much like the last one

Housekeeping
========================================================

- A lot of energy goes into basic housekeeping of analysis
  - Data preparation: checks, reshaping, etc.
  - Analysis: assumption checks, linking results to data
  - Graphs, tables: keeping up to data with data, results.
  - Version control: How is today's data different from the last set?
  - Logging: What did I do last time? 
- A tidy project helps keep YOU organised, focused
  - It also helps others see what you're doing.
  
Reproducibility is a thing
========================================================

- Reproducibility = being able to get from your data to the 
report content again and again and again.
- Better still, OTHER people being able to recreate what YOU did.
- Why is this a good thing?
  - Credibility in your results (I didn't HACK this, honest!)
  - When new data comes in you can "push a button" and get the new report.

Workflow
========================================================

- A flow of work?
- Yup.
  - From data to report.
- Scripts help
  - You can see what changes you made
  - Others can see too
  - If you break work into chunks then you can build new analysis like Lego.

Workflow
========================================================

![Data Science diagram](https://github.com/hadley/r4ds/blob/master/diagrams/data-science.png)

How does R help?
========================================================

- Not so much R, as all the tools that go with R.
- You CAN do this with other tools (python, Excel even)
  - Script-based tools like python & R are more suited to building workflow
  - It's POSSIBLE, just harder in Excel
- R has a mountain of tools to help...

What kinds of things are we talking about?
========================================================

- [ProjectTemplate](http://projecttemplate.net)
  - Basic project structure. TIDY!
- [Tidyverse](https://www.tidyverse.org)
  - Get data ([readr](http://readr.tidyverse.org), [readxl](http://readxl.tidyverse.org), [haven](http://haven.tidyverse.org), [rvest](https://github.com/hadley/rvest), [jsonlite](https://github.com/jeroen/jsonlite#jsonlite), [xml2](https://github.com/r-lib/xml2))
  - Check data ([tibble](http://tibble.tidyverse.org), [dplyr](http://dplyr.tidyverse.org), [stringr](http://stringr.tidyverse.org), [lubridate](http://lubridate.tidyverse.org), [forcats](http://forcats.tidyverse.org))
  - Reshape data ([tidyr](http://tidyr.tidyverse.org), [dplyr](http://dplyr.tidyverse.org))
  - Analyse data ([purrr](http://purrr.tidyverse.org), ...)
  - Graph data ([ggplot2](http://ggplot2.tidyverse.org))
  - Report data ([rmarkdown](http://rmarkdown.rstudio.com), [RStudio Notebooks](http://rmarkdown.rstudio.com/r_notebooks.html))

RNotebooks?
========================================================

- In RStudio, you can create a new file "R Notebook"
  - Text description of WHAT you're doing (and WHY!)
  - Inline R code
    - Can show code, or hide and only show results
  - Output is stored WITH the text and code
  - Allows anyone else to see (and review) WHAT, WHY, HOW
  - REPRODUCIBILITY baked in!
  
Version control
========================================================

![PhDComics](http://www.phdcomics.com/comics/archive/phd101212s.gif)

Version control
========================================================

- Today's code + today's data + today's analysis = today's report
- Today's code + tomorrow's data + ...
- Tomorrow's code + today's data + tomorrow's analysis = ...
- WHAT HAS CHANGED!?!?!?!!!?!

Version control
========================================================

- More housekeeping!
- Tools like GitHub help keep things neat and tidy
  - Branch to create tomorrow's analysis
  - Commit messages to keep track of WHY things changed
    - Diffs take care of WHAT changed
  - Helps review
    - Let's discuss these changes
  - Collaborate!
- Git (and SVN) is baked into RStudio

Good resources
========================================================

- [RStudio](https://www.rstudio.com)
  - [Webinars](https://www.rstudio.com/resources/webinars/)
- [Jenny Bryan](https://speakerdeck.com/jennybc) 
  - [Workflow - you should have one](https://speakerdeck.com/jennybc/workflow-you-should-have-one)
- [Hadley Wickham](http://hadley.nz)
  - [R for Data Science (R4DS)](http://r4ds.had.co.nz)
- [Mara Averick](https://maraaverick.rbind.io)
  - [R Workflow fun](https://maraaverick.rbind.io/2017/09/r-workflow-fun/)
