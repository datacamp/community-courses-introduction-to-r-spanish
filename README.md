## Introduction to R in Spanish: Introducción a R

Alvaro Fuentes has translated the original introduction to R course ([GitHub](www.github.com/datacamp/courses-intro-to-r-old)) to Spanish. This repository contains all the source files, in Spanish, that correspond to the course that is live on DataCamp.

```R
# get latest version of datacamp
library(devtools)
install_github("datacamp/datacamp")

# upload all chapters
library(datacamp)
datacamp_login("spanish@datacamp.com", "pass", "")
upload_course(upload_chapters = TRUE, open = FALSE)
```