# Python-EDA-Crime-Data
An exploratory data analysis of global homicide rates and counts by region.

This project is an **Exploratory Data Analysis (EDA)** of a global homicide dataset. It involves data cleaning, transformation, and a series of visualizations to uncover trends and patterns in homicide rates and counts across different countries, regions, and subregions over time.

## 📊 Project Overview

The analysis performs the following key steps:
1.  **Data Loading & Inspection:** Imports the dataset and examines its structure.
2.  **Data Cleaning:** Checks for and handles null values; corrects data types.
3.  **Data Transformation:** Groups and aggregates data for various analyses.
4.  **Visualization:** Creates multiple plots to answer specific questions about the data, including:
    - A pie chart of the top 5 countries by homicide count.
    - Bar plots of total homicides by Region and Subregion.
    - A line chart comparing trends in Asia and Europe since 2016.
    - A treemap visualizing homicide counts by Subregion.

## 📈 Key Visualizations

*   **Top 5 Countries by Count (Pie Chart)** 
*   **Homicides by Region (Bar Plot)** 
*   **Homicides by Subregion (Bar Plot/Treemap)** 
*   **Asia vs. Europe Post-2016 (Line Chart)** 
*   **Total Rate by Year (Line Chart)** 

## 🛠️ Technologies Used

*   **Python 3**
*   **Pandas:** For data manipulation and analysis.
*   **Matplotlib:** For creating static, interactive, and animated visualizations.
*   **Seaborn:** For making statistically informative and attractive visualizations.
*   **Plotly Express:** For creating interactive plots and treemaps.

## 📁 Dataset

The dataset (`homicide_by_countries.csv`) contains the following columns:
*   `Location`: Country name.
*   `Region`: The major region of the world (e.g., Americas, Asia, Europe).
*   `Subregion`: A more specific area within a region (e.g., South America, Southern Europe).
*   `Rate`: The homicide rate per 100,000 people.
*   `Count`: The absolute number of homicide incidents.
*   `Year`: The year the data was recorded.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python and Jupyter Notebook (or Jupyter Lab) installed on your system.

### Installation

1.  Clone this repository:
    ```bash
    git clone <your-repo-url>
    cd global-homicide-analysis
    ```

2.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3.  Launch Jupyter Notebook and open `Untitled1.ipynb`:
    ```bash
    jupyter notebook
    ```

4.  Update the file path in the second code cell to point to the location of your `homicide_by_countries.csv` file.
    ```python
    df = pd.read_csv("path/to/your/homicide_by_countries.csv")
    ```

5.  Run all cells to execute the analysis and generate the visualizations.

