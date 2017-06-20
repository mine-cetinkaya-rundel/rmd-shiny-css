# rmd-shiny-css

Unexpected (to me) behaviour when embedding a Shiny app in an R Markdown document and styling with CSS: 

You can take a look at the screenshots folder if you want a peek without running the code. 

In a nutshell, what I'm seeing is that when `runtime: shiny` is used in an Rmd, div ids get `"section-"` appended in the rendered output. Hence, styling will be applied correctly if the div id is named as `"section-blah"` in the css. 

I could not find any documentation around this. Is this expected behaviour? If so, why?
