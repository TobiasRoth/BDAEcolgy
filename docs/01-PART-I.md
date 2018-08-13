
# (PART) BAYESIAN DATA ANALYSIS {-}

# Introduction to PART I {#PART-I}



> hier kommt eine Bemerkung

## Data handling
Alle Packete laden `library(tidyverse)` oder nur `library(tidyverse)`.



```r
dat <- iris %>% 
  as.tibble() %>% 
  filter(Sepal.Length > 5) %>% 
  group_by(Species) %>% 
  summarise(n = n(),
            mittel = mean(Petal.Length))
```
