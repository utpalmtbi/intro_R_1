# R for Biologists: From Zero to Data Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/utpalmtbi/intro_R_1/blob/main/The_First_Course_on_R.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/utpalmtbi/intro_R_1/main?filepath=The_First_Course_on_R.ipynb)

A comprehensive, hands-on introductory course designed specifically for **biologists and life scientists with no prior programming experience**.
Learn R by solving real biological problems—from optical density measurements and qPCR Ct values to differential gene expression analysis.

---

## Content Origin

The educational materials in this repository are adapted and reorganised from my original content, previously published on the Bakshi Lab website ([Part 1: R Basics](https://www.bakshilab.org/blog/basic_r_1) and [Part 2: Visualizing Data in R](https://www.bakshilab.org/blog/basic_r_2)), along with *Introduction to Inferential Statistics* lecture modules. This repository provides an accompanying computational and practical resource for the educational material.

---

## Run Instantly in Your Browser

You do not need to install anything on your computer! Click the badge below to open the notebook directly in **Google Colab** (with an R kernel):

**[Open The_First_Course_on_R.ipynb in Google Colab](https://colab.research.google.com/github/utpalmtbi/intro_R_1/blob/main/The_First_Course_on_R.ipynb)**

> **Tip:** When opening in Google Colab, the notebook automatically connects to an R runtime. Run code cells sequentially with `Shift + Enter` or by clicking the **Play** button next to each cell.

---

## Course Curriculum

### Part I: Core Foundations of R Programming

1. **Variables — Your Lab Notebook in Code**
   * Storing measurements (OD₆₀₀, spleen weights)
   * Assignment operators (`<-`) and basic calculations
2. **Vectors — Your First R Data Structure**
   * Combining values with `c()`
   * Data types: numeric, integer, character, logical
   * qPCR Ct values and cell counts
3. **Vector Operations & Filtering**
   * Element-wise arithmetic
   * Logical indexing and threshold filtering
4. **Data Frames — Biological Spreadsheets**
   * Creating, inspecting, and manipulating sample sheets
   * Accessing columns (`$`), filtering rows, adding calculated columns
5. **Matrices & 3D Arrays**
   * High-throughput gene expression matrices
   * Time-course multi-treatment experiment arrays
6. **Factors & Categorical Variables**
   * Experimental conditions, genotypes, and stages
7. **Control Flow & Functions**
   * Conditional logic (`if` / `else`) for classifying hits
   * Custom reusable functions for biological calculations
8. **File Input / Output (I/O)**
   * Importing and exporting CSV spreadsheets (`read.csv`, `write.csv`)
9. **Cap-stone Project: Drug Response RNA-seq Analysis**
   * End-to-end analysis: fold-change calculation, classification of up/downregulated genes, and exporting publication-ready summaries

---

### Part II: Inferential Statistics & Data Visualization (Bakshi Lab Edition)

*Every topic features a two-tier approach: **⚡ Minimum Code** (ultra-concise 1-line syntax for first-time learners) followed by **🔬 Detailed Code** (publication-ready formatting, custom palettes, diagnostic extraction, and statistical annotations).*

10. **Independent Samples $t$-test & Box Plot** (`t.test`, `boxplot`)
11. **Paired $t$-test & Profile Line Plot** (`t.test(..., paired=TRUE)`, `matplot`)
12. **One-Sample $t$-test & Histogram** (`t.test(..., mu=...)`, `hist`, `abline`)
13. **Chi-Square ($\chi^2$) Goodness-of-Fit & Grouped Bar Plot** (`chisq.test`, `barplot`)
14. **Mann-Whitney $U$ Test & Comparative Box Plot** (`wilcox.test`)
15. **Wilcoxon Signed-Rank Test & Paired Line Plot** (`wilcox.test(..., paired=TRUE)`)
16. **Pearson Correlation & Scatter Plot with Trendline** (`cor.test`, `plot`, `abline`)
17. **Spearman Rank Correlation & Monotonic Trajectory Plot** (`cor.test(..., method="spearman")`)
18. **Simple Linear Regression & Prediction Visualization** (`lm`, `predict`)
19. **One-Way ANOVA with Tukey HSD Post-Hoc & Comparative Box Plots** (`aov`, `TukeyHSD`)
20. **Kruskal-Wallis Multi-Group Test & Median Ranking Plot** (`kruskal.test`)
21. **Clustered Heatmaps for Multi-Variable & Omics Data** (`heatmap`, `pheatmap`)
22. **Comprehensive Decision Guide & Statistical Cheatsheet**

---

## Running Locally

If you prefer to run the notebook on your local computer:

1. Clone this repository:

   ```bash
   git clone https://github.com/utpalmtbi/intro_R_1.git
   cd intro_R_1
   ```
2. Open `The_First_Course_on_R.ipynb` in:

   * **VS Code** with Jupyter & R extensions installed
   * **JupyterLab** / **Jupyter Notebook** with the `IRkernel` package installed
   * **Positron** or **RStudio**
