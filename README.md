# Student Performance Analysis

This project analyzes student performance data from two Portuguese secondary schools to uncover the strongest predictors of academic success. The dataset includes demographic, social, and academic factors.

## Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance)
- **Instances**: 649 students
- **Features**: 30 (e.g., grades, study time, failures, absences)
- **Subject**: Mathematics

## Project Structure

```plaintext
student-performance-analysis/
├── data/
│   └── student-mat.csv
├── R/
│   └── student-performance-analysis.Rmd
├── output/
│   └── student-performance-analysis.html  # This file is generated after knitting the Rmd
├── .gitignore
└── README.md
```

## Analysis

The analysis involves:
1. **Exploratory Data Analysis (EDA)**: Summarizing and visualizing the dataset.
2. **Data Cleaning**: Handling missing values and converting categorical variables.
3. **Correlation Analysis**: Investigating relationships between numerical variables.
4. **Regression Model**: Predicting final grades using a linear regression model.
5. **Data Visualization**: Visualizing relationships between study time, failures, and final grades.

## View the Analysis

You can view the analysis report in PDF format by clicking the link below:

[Download the Analysis PDF](https://github.com/farhanataiyebah/student-performance-analysis/blob/master/output/student-performance-analysis.pdf)


## Requirements

The project uses the following R packages:
* `tidyverse`
* `ggplot2`
* `dplyr`
* `readr`
* `knitr`
* `rmarkdown`

Run the `setup` code chunk in `student-performance-analysis.Rmd` to install and load these packages.

## How to Run

1. Download the repository.
2. Set your working directory to the project folder in RStudio.
3. Open the `student-performance-analysis.Rmd` file.
4. Run the code chunk by chunk or render the whole file to generate the HTML output:

```r
rmarkdown::render("R/student-performance-analysis.Rmd")
```

This will generate the `student-performance-analysis.html` file in the `output/` folder.