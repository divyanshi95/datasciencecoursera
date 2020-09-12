---
output: 
  pdf_document: default
---
## This is a markdown file
## Are the hashtags necessary
 
```
{r, include = TRUE}
install.packages("readxl")
library(readxl)
norway <- read_excel("C:/Users/rsvoh_000/Desktop/R/norway.xlsx")
summary(norway)
```

## HITANSHI IS DUMB