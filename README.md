# Survival-Analysis-of-Ovarian-Carcinoma-Patients-in-Clinical-Trials

This repository contains a comprehensive analysis of the survival outcomes of patients with ovarian carcinoma who were enrolled in clinical trials. The focus is on comparing the survival outcomes between different treatment groups using Kaplan-Meier estimators and log-rank tests.
 
<img src="https://github.com/lokesh97jain/Survival-Analysis-of-Ovarian-Carcinoma-Patients-in-Clinical-Trials/assets/44944748/be044dde-f89a-4dc7-9f8e-8e254fe89b0c" height="40%" width="40%">

## Project Overview
The Kaplan-Meier estimator is used to estimate and plot survival probability over time through a non-parametric approach. The analysis is conducted using the Ovarian dataset, which comprises clinical data from 26 ovarian carcinoma patients. This dataset includes crucial information such as patient age, treatment type, and survival status. The primary endpoint of interest is the time to an event, specifically the time to death or censoring.

## Prerequisites
To run this analysis, you need R installed along with RStudio to easily manage R Markdown files. Ensure you have the following R packages installed:

  * **survival** for conducting survival analyses
  * **ggplot2** for creating visualizations
  * **dplyr** for data manipulation
  * **knitr** for compiling the R Markdown file

You can install these packages using the following R command:

```bash
install.packages(c("survival", "ggplot2", "dplyr", "knitr"))
```

## Running the Analysis
To view and run the R Markdown file, open it in RStudio and use the 'Knit' button to compile the document into your desired output format, such as HTML, PDF, or Word.

#### Install knit 
``` bash
install.packages("knitr")
```

## Results and Discussion

<img src="https://github.com/lokesh97jain/Survival-Analysis-of-Ovarian-Carcinoma-Patients-in-Clinical-Trials/assets/44944748/d83be9c7-e2cb-4519-aef6-a825f1661c59" height="50%" width="50%">

The chart illustrates the survival curves along with confidence intervals for two treatment groups in a study: "rx=1" for cyclophosphamide alone and "rx=2" for a combination of cyclophosphamide and adriamycin. The survival curve for the first group shows a steady decline, with a survival probability of 43.1% at nearly 21 months. The second group fares slightly better, demonstrating a survival probability of 56.4% at 18.5 months. To assess the significance of the survival differences between the two groups, a log-rank test was performed. This test yielded a chi-square value of 1.1 with one degree of freedom and a p-value of 0.3, suggesting that there is no statistically significant difference in survival outcomes between the two treatment regimens for ovarian carcinoma patients in these clinical trials.

## Conclusion
The survival rates of ovarian cancer patients in clinical trials, examining the effects of various treatment methods. The findings suggest that a combination of cyclophosphamide and adriamycin might modestly enhance survival compared to using cyclophosphamide alone, although the difference between the treatment groups was not statistically significant. Further studies with larger sample sizes may be necessary to provide more definitive results. Overall, this study highlights the importance of survival analysis in assessing treatment options for ovarian carcinoma patients in clinical trials.
