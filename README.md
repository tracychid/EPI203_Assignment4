# EPI 203 - Assignment 4: Reproducible Report

This manuscript studies the relationship between cost and the risk for a cardiac event controlling for female, smoke, and age using logistic regression analysis on synthetic data.

**PDF Manuscript**

The PDF version of this manuscript can be found in the **EPI203_Reproducible_Report.pdf** file

**Reproducible Code**

If you are interested in reproducing this work, all code is found in the **index.qmd** file. All data used for this study are publicly accessible at <https://github.com/MethodsForReproducibleHealthResearch/Assignment2>. The data are synthetic and created by the Dept. of Health Policy, Stanford University for learning purposes. All analyses were performed in RStudio (Version 2026.04.0+526). For further information, please contact the corresponding author.

1.  To run the code yourself, clone this repo and open as a project in RStudio.
2.  To generate the publishable PDF from scratch using the raw-data, run:

```{bash}
quarto render index.qmd --to pdf
```

To clean up generated files:

```{bash}
rm -rf ./_manuscript ./_freeze ./_temp_workspace
```

**AI Statement**

Generative AI technology (e.g., ChatGPT) was not used to complete any portion of the work.
