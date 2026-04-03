# Baby-Names

This project demonstrates data wrangling and string manipulation techniques in R using the `babynames` dataset. The analysis is performed in the `Baby-Names.Rmd` R Markdown file, which guides you through several data transformation steps and outputs results in a clear, reproducible format.

## Baby-Names.Rmd — Analysis Overview

### Purpose
The R Markdown file demonstrates data wrangling, string manipulation, and reporting techniques in R using the `babynames` dataset. It is designed as a step-by-step guide for transforming, filtering, sampling, and summarizing baby name data, with clear explanations and reproducible code.

### Workflow Summary
1. **Setup**: Loads required libraries (`tidyverse`, `babynames`, `janitor`, `knitr`).
2. **Mutate Proportion to Percentages**: Adds a `prop_percent` column to show the proportion of each name as a rounded percentage.
3. **String Formatting**: Creates a `percent_year` column combining percentage and year into a formatted string.
4. **Filtering**: Filters the dataset for the name "Cora" and female entries only.
5. **Random Sampling**: Selects five random rows for "Cora" (female), sorted by year.
6. **String Collapsing**: Collapses the sampled rows into a single, readable string.
7. **String Gluing**: Embeds the collapsed string into a summary sentence for reporting.

### How to Use
1. Open `Baby-Names.Rmd` in RStudio or another R Markdown-compatible editor.
2. Install the required R packages if you haven't already:
	- `tidyverse`
	- `babynames`
	- `janitor`
	- `knitr`
	- `stringr`
3. Click the **Knit** button to generate the HTML output and view the results.

### Output
- The Rmd file produces formatted tables and summary sentences, demonstrating each transformation step.
- The final output includes a sentence summarizing the representation of the name "Cora" among female baby names for selected years.

### Author
Mia Fitzgerald  
April 2026