# R for Biologists: From Zero to Data Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/utpalmtbi/intro_R_1/blob/main/The_First_Course_on_R.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/utpalmtbi/intro_R_1/main?filepath=The_First_Course_on_R.ipynb)

A comprehensive, hands-on introductory course designed specifically for **biologists and life scientists with no prior programming experience**. 

Learn R by solving real biological problems—from optical density measurements and qPCR Ct values to differential gene expression analysis.

---
## Content Origin
The educational materials in this repository are adapted and reorganised from my original content, previously published on [the Bakshi Lab website](https://www.bakshilab.org/blog/basic_r_1). This repository provides an accompanying computational and practical resource for the original educational material.

---
## Run Instantly in Your Browser

You do not need to install anything on your computer! Click the badge below to open the notebook directly in **Google Colab** (with an R kernel):

 **[Open The_First_Course_on_R.ipynb in Google Colab](https://colab.research.google.com/github/utpalmtbi/intro_R_1/blob/main/The_First_Course_on_R.ipynb)**

> **Tip:** When opening in Google Colab, the notebook automatically connects to an R runtime. Run code cells sequentially with `Shift + Enter` or by clicking the **Play** button next to each cell.

---

## Course Curriculum

1. **Variables — Your Lab Notebook in Code**
   - Storing measurements (OD₆₀₀, spleen weights)
   - Assignment operators (`<-`) and basic calculations
2. **Vectors — Your First R Data Structure**
   - Combining values with `c()`
   - Data types: numeric, integer, character, logical
   - qPCR Ct values and cell counts
3. **Vector Operations & Filtering**
   - Element-wise arithmetic
   - Logical indexing and threshold filtering
4. **Data Frames — Biological Spreadsheets**
   - Creating, inspecting, and manipulating sample sheets
   - Accessing columns (`$`), filtering rows, adding calculated columns
5. **Matrices & 3D Arrays**
   - High-throughput gene expression matrices
   - Time-course multi-treatment experiment arrays
6. **Factors & Categorical Variables**
   - Experimental conditions, genotypes, and stages
7. **Control Flow & Functions**
   - Conditional logic (`if` / `else`) for classifying hits
   - Custom reusable functions for biological calculations
8. **File Input / Output (I/O)**
   - Importing and exporting CSV spreadsheets (`read.csv`, `write.csv`)
9. **Cap-stone Project: Drug Response RNA-seq Analysis**
   - End-to-end analysis: fold-change calculation, classification of up/downregulated genes, and exporting publication-ready summaries

---

## Running Locally

If you prefer to run the notebook on your local computer:

1. Clone this repository:
   ```bash
   git clone https://github.com/utpalmtbi/intro_R_1.git
   cd intro_R_1
   ```
2. Open `The_First_Course_on_R.ipynb` in:
   - **VS Code** with Jupyter & R extensions installed
   - **JupyterLab** / **Jupyter Notebook** with the `IRkernel` package installed
   - **Positron** or **RStudio**
