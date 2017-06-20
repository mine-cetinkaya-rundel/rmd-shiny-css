# rmd-shiny-css

Unexpected (to me) behaviour when embedding a Shiny app in an R Markdown document and styling with CSS: 

You can take a look at the screenshots folder if you want a peek without running the code. 

In a nutshell, when `runtime: shiny` is used in an Rmd, div ids get `"section-"` prepended in the rendered output. Hence, styling is applied correctly to a div named `"blah"` if the div id is defined as `"section-blah"` in the css. 

I could not find any documentation around this. Is this expected? If so, why?
