This repository records the R script of a R Shiny App project, which automates the data analysis and visualization of Catnip Quality Control (QC) samples. 
This Shiny app is part of bigger project, that has yielded multiple publications in well known journals, as listed in the following citations:


- Patel H, Gomes EN, Yuan B, Lyu W, Wu Q, Simon JE. **Investigation of Volatile Iridoid Terpenes in Nepeta cataria L. (Catnip) Genotypes.** Molecules. 2022; 27(20):7057. [**(see original article)**](https://www.mdpi.com/1420-3049/27/20/7057)

- Gomes, E. N., Patel, H., Yuan, B., Lyu, W., Juliani, H. R., Wu, Q., & Simon, J. E. (2023). **Successive harvests affect the aromatic and polyphenol profiles of novel catnip (Nepeta cataria L.) cultivars in a genotype-dependent manner**. Frontiers in Plant Science, 14, 1121582. [**(see original article)**](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2023.1121582/full)

- Gomes, E. N., Yuan, B., Patel, H. K., Lockhart, A., Wyenandt, C. A., Wu, Q., & Simon, J. E. (2024). **Implications of the Propagation Method for the Phytochemistry of Nepeta cataria L. throughout a Growing Season.** Molecules, 29(9), 2001. [**(see original article)**](https://www.mdpi.com/1420-3049/29/9/2001)

------

The R code has been developed with reference to [**R for Data Science (2e)**](https://r4ds.hadley.nz/), and the official documentation of [**tidyverse**](https://www.tidyverse.org/), and [**DataBrewer.co**](https://www.databrewer.co/). See breakdown of modules below:

- **Data visualization** with **ggplot2** ([**tutorial**](https://www.databrewer.co/R/visualization/introduction) of the fundamentals; and [**data viz. gallery**](https://www.databrewer.co/R/gallery)).

- [**Data wrangling**](https://www.databrewer.co/R/data-wrangling) with the following packages:
[**tidyr**](https://www.databrewer.co/R/data-wrangling/tidyr/introduction): transform (e.g., pivoting) the dataset into tidy structure; [**dplyr**](https://www.databrewer.co/R/data-wrangling/dplyr/0-introduction): the basic tools to work with data frames; [**stringr**](https://www.databrewer.co/R/data-wrangling/stringr/0-introduction): work with strings; [**regular expression**](https://www.databrewer.co/R/data-wrangling/regular-expression/0-introduction): search and match a string pattern; [**purrr**](https://www.databrewer.co/R/data-wrangling/purrr/introduction): functional programming (e.g., iterating functions across elements of columns); and [**tibble**](https://www.databrewer.co/R/data-wrangling/tibble/introduction): work with data frames in the modern tibble structure.

