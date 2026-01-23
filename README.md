# Global Terrorism Database (GTD) - Exploratory Data Analysis

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-informational)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Latest-blueviolet)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Latest-orange)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Latest-success)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)](https://jupyter.org/)

### Project Overview
This project focuses on performing a comprehensive **Exploratory Data Analysis (EDA)** on the Global Terrorism Database. The primary objective is to uncover patterns, trends, and insights regarding global terrorist incidents over several decades. By leveraging Python's data science ecosystem, the project moves from raw data ingestion to insightful visualizations, highlighting the evolution of global security challenges.

This repository serves as a **portfolio-level project** demonstrating:

- Data cleaning, wrangling, and preprocessing
- Univariate, bivariate, and comparative analysis
- Advanced visualization using Seaborn and Matplotlib.
- Real insights driven from real-world datasets

---

### Technical Stack
The analysis was performed using the following tools and libraries:

* **Python:** The core programming language used for the entire pipeline.
* **Jupyter Notebook:** The interactive environment used for prototyping and documentation.
* **NumPy:** For efficient numerical computations and array handling.
* **Pandas:** Used extensively for data loading, cleaning, merging datasets, and feature engineering.
* **Matplotlib:** For the foundational layer of static visualizations.
* **Seaborn:** Employed to create high-level, aesthetically pleasing statistical graphics.

---

### Dataset Description & Integration
The analysis is primarily based on the **Global Terrorism Database (GTD)**, an open-source database including information on terrorist attacks around the world from 1970 through 2017. 

**Key Enhancement:** To provide deeper context, I integrated a secondary **Global Population Dataset**. By merging this with the GTD, I was able to derive normalized insights, calculating incident rates per capita rather than looking at absolute numbers alone. This helps in understanding the true impact of terrorism relative to the population size of various regions and countries, ensuring a more accurate comparative analysis.

---

### Analysis Workflow
1.  **Data Loading & Preprocessing:**  Handling large-scale datasets and filtering relevant columns.
    * Addressing missing values and ensuring data type consistency.
2.  **Data Cleaning:**  Renaming cryptic column names for better readability.
    * Standardizing categorical data for accurate grouping and aggregation.
3.  **Exploratory Data Analysis (EDA):**
    * **Temporal Analysis:** Tracking the rise and fall of incidents across years.
    * **Geographical Mapping:** Identifying "Hot Zones" of terrorist activity.
    * **Attack & Target Profiling:** Analyzing preferred methods of attack and the most frequent targets.
    * **Per Capita Impact:** Utilizing the merged population data to compare the density of incidents across different demographics.

---

### 🚀 How to Run
To replicate this analysis on your local machine, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/anvony/gtd-eda-project.git
    cd gtd-eda-project
    ```

2.  **Set up Environment:**
    Ensure you have Python installed. It is recommended to use a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    pip install numpy pandas matplotlib seaborn jupyter
    ```

3.  **Launch the Notebook:**
    ```bash
    jupyter notebook gtd_eda.ipynb
    ```

---

### Future Work
To further extend this project, the following steps could be taken:
* **Predictive Modeling:** Implementing Machine Learning models to predict the potential success or failure of an attack based on historical patterns.
* **Sentiment Analysis:** Scrapping news data related to specific events to analyze the global sentiment following major incidents.
* **Interactive Dashboards:** Utilizing **Plotly** or **Tableau** to create interactive maps that allow users to filter data by region and decade in real-time.


---

*Contributions and feedback are welcome.*