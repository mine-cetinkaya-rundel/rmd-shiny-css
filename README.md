# rmd-shiny-css

Embedding a Shiny app in an R Markdown document and styling with CSS


Unexpected (to me) behaviour in Rmd documents with embedded shiny apps that use a custom CSS: 

You can take a look at the screenshots folder if you want a peek without running the code. 

In a nutshell, what I'm seeing is that when runtime: shiny is used in an Rmd, div ids get appended "section-" in the rendered output. Hence, styling is only applied correctly if the div id is named as "section-blah" in the css. 

I could not find any documentation around this, and I'm not sure if this, is this expected? If so, why?
