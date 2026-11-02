# R for Biologists: From Zero to Data Analysis

**A practical introduction to R programming for biology and life science researchers.**

Developed by **Dr. Utpal Bakshi | Bakshi Lab | Presidency University, Kolkata, India**

---

## About This Course

**R for Biologists: From Zero to Data Analysis** is a hands-on introductory course designed specifically for biologists, life science students and researchers with little or no prior programming experience.

The course introduces the fundamentals of R programming through biological examples and research-oriented problems. Rather than learning programming concepts in isolation, learners explore how R can be used to organise, manipulate, analyse and interpret biological data.

Examples range from basic laboratory measurements and qPCR Ct values to gene expression data and drug response analysis.

The accompanying Jupyter Notebook provides an interactive environment for practising the concepts introduced throughout the course.

## Course Information

| Parameter            | Description                                                      |
| -------------------- | ---------------------------------------------------------------- |
| Course title         | R for Biologists: From Zero to Data Analysis                     |
| Programming language | R                                                                |
| Difficulty level     | Beginner                                                         |
| Prerequisites        | No prior programming experience required                         |
| Learning format      | Interactive Jupyter Notebook                                     |
| Target audience      | Biology and life science students, researchers and professionals |
| Resource type        | Open educational resource                                        |

## Learning Objectives

By the end of this course, learners will be able to:

1. Understand the fundamental concepts and syntax of R programming.
2. Work with essential R data structures, including vectors, matrices, arrays and data frames.
3. Perform arithmetic, logical and vector operations.
4. Manipulate and filter biological datasets.
5. Understand and use categorical variables and factors.
6. Implement conditional statements, loops and user-defined functions.
7. Import and export datasets using common file formats.
8. Apply basic R programming techniques to biological data analysis.
9. Perform introductory gene expression and drug response analysis using R.

## Who Is This Course For?

This course is particularly suitable for:

* Undergraduate and postgraduate students in biological sciences.
* Students of biotechnology, microbiology, biochemistry and biomedical sciences.
* Life science researchers interested in computational biology.
* Researchers beginning their journey in bioinformatics and data science.
* Laboratory scientists interested in analysing experimental data using R.

**No previous programming experience is necessary.**

---

## Course Curriculum

The course is organised into nine major learning modules.

### 1. Variables — Your Lab Notebook in Code

* Understanding variables and assignment in R.
* Storing biological measurements.
* Assignment operators (`<-`) and basic calculations.
* Examples using optical density (OD₆₀₀) and biological measurements.

### 2. Vectors — Your First R Data Structure

* Creating vectors using `c()`.
* Understanding numeric, integer, character and logical data types.
* Working with biological measurements.
* Examples using qPCR Ct values and cell counts.

### 3. Vector Operations and Filtering

* Element-wise arithmetic operations.
* Logical operators and conditions.
* Logical indexing and threshold-based filtering.
* Extracting relevant observations from biological datasets.

### 4. Data Frames — Biological Spreadsheets

* Creating and inspecting data frames.
* Accessing rows and columns.
* Adding calculated variables.
* Filtering and manipulating sample metadata.

### 5. Matrices and 3D Arrays

* Creating and manipulating matrices.
* Understanding multidimensional data structures.
* Representing high-throughput gene expression data.
* Working with time-course and multi-treatment experimental data.

### 6. Factors and Categorical Variables

* Understanding categorical variables.
* Creating and manipulating factors.
* Representing experimental conditions, genotypes and developmental stages.

### 7. Control Flow and Functions

* Introduction to conditional statements.
* Implementing `if`, `else` and related logical structures.
* Writing reusable user-defined functions.
* Applying conditional logic to biological classification problems.

### 8. File Input and Output

* Importing external datasets into R.
* Reading CSV files using `read.csv()`.
* Exporting analytical results using `write.csv()`.
* Managing biological datasets programmatically.

### 9. Capstone Project: Drug Response RNA-seq Analysis

* Applying the concepts learned throughout the course.
* Working with gene expression data.
* Calculating fold changes.
* Classifying upregulated and downregulated genes.
* Generating and exporting summary tables.

---

## Access the Course Notebook

The complete course is provided as an interactive Jupyter Notebook.

**Main course notebook:**
[`The_First_Course_on_R.ipynb`](https://github.com/utpalmtbi/intro_R_1/blob/main/The_First_Course_on_R.ipynb)

You can view the notebook directly on GitHub or download it for local execution.

### Running the Notebook Locally

To execute the notebook on your computer:

**Step 1. Clone the repository**

```bash
git clone https://github.com/utpalmtbi/intro_R_1.git
cd intro_R_1
```

**Step 2. Install R and Jupyter Notebook/JupyterLab.**

**Step 3. Install and register the R kernel.**

Open an R session and execute:

```r
install.packages("IRkernel")
IRkernel::installspec(user = TRUE)
```

**Step 4. Open the notebook**

Launch Jupyter Notebook or JupyterLab and open:

`The_First_Course_on_R.ipynb`

Select the R kernel and execute the code cells sequentially.

---

## About the Author

**Dr. Utpal Bakshi**
Assistant Professor
Institute of Health Sciences
Presidency University, Kolkata, India.

**Research interests:** Bioinformatics, computational biology, microbiome research, population genomics and multi-omics data analysis.

**Website:** [Bakshi Lab](https://www.bakshilab.org)

**Educational Resources:** [Bakshi Lab Blog](https://www.bakshilab.org/blog)

**GitHub:** [utpalmtbi](https://github.com/utpalmtbi)

---

## Content Origin and Attribution

The educational content presented in this repository originates from my own educational materials, originally published on the [Bakshi Lab website](https://www.bakshilab.org/blog/basic_r_1).

This GitHub repository provides an accompanying computational resource, presenting the learning material through an interactive Jupyter Notebook with practical examples and programming exercises.

---

## How to Cite

Bakshi, U. *R for Biologists: From Zero to Data Analysis*. GitHub repository.
https://github.com/utpalmtbi/intro_R_1/

---

## Feedback and Suggestions

Suggestions, corrections and feedback that could improve the learning experience are welcome.

Please use the [GitHub Issues](https://github.com/utpalmtbi/intro_R_1/issues) section to report errors or suggest improvements.

---

**© Utpal Bakshi | Bakshi Lab | Presidency University, Kolkata, India**

*Making computational biology accessible through practical learning.*









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
