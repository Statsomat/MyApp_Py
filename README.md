# MyApp_Py

For contributors to the [Statsomat](https://statsomat.com) portal: Container for a new Statsomat app based on Shiny, R and Python via `reticulate`. 

Please update the `Renviron` for example when uploading to [Shinyapps.io](https://www.shinyapps.io/). 

To integrate your automated data analysis, start with the files:
 
```
server.R
report.Rmd (calls report_kernel.Rmd as a child document)
report_code_container.Rmd (calls report_code.Rmd as a child document)
```

Other core files: `global.R` (global settings), `ui.R` (contains the GUI).  

If you need help, contact support@statsomat.com. 
