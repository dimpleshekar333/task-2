# Titanic Dataset Analysis

This project performs **Exploratory Data Analysis (EDA)** on the Titanic
dataset using Python. It covers loading the dataset, handling missing
values, visualizing data, and gaining insights from features.

## **Project Structure**

-   Load dataset\
-   Check dataset information and missing values\
-   Handle missing values\
-   Exploratory Data Analysis (EDA)
    -   Histograms\
    -   Boxplots\
    -   Correlation Matrix\
    -   Pairplots\
    -   Interactive Visualization\
-   Feature-level insights

------------------------------------------------------------------------

## **Requirements**

Install the required Python libraries before running the code:

``` bash
pip install pandas numpy matplotlib seaborn plotly
```

------------------------------------------------------------------------

## **Code Overview**

### **1. Import Libraries**

``` python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
```

### **2. Load Dataset**

``` python
file_path = r"C:\Users\Dimple.S\Downloads\Titanic-Dataset (5).csv"
df = pd.read_csv(file_path)
```

### **3. Basic Info & Summary Statistics**

-   Display first 5 rows\
-   Dataset information (`info()`)\
-   Summary statistics (`describe()`)

### **4. Missing Values**

-   Check missing values using `isnull().sum()`\
-   Fill missing values:
    -   For categorical columns → mode\
    -   For numeric columns → median

### **5. Exploratory Data Analysis (EDA)**

#### **a. Histograms**

-   Visualize the distribution of numeric features.

#### **b. Boxplots**

-   Detect outliers for each numeric column.

#### **c. Correlation Matrix**

-   Check correlations using a heatmap.

#### **d. Pairplot**

-   Explore relationships between numeric features.

#### **e. Interactive Visualization**

-   Use Plotly for interactive plots (e.g., Age vs Survived).

------------------------------------------------------------------------

## **Usage**

1.  Save the Python code in a file, e.g., `titanic_analysis.py`.\
2.  Update the `file_path` with the correct dataset location.\
3.  Run the code:

``` bash
python titanic_analysis.py
```

4.  Visualizations will be displayed one by one.

------------------------------------------------------------------------

## **Outputs**

-   **Histograms** for numeric features\
-   **Boxplots** to detect outliers\
-   **Correlation heatmap**\
-   **Pairplots** for relationships\
-   **Interactive histogram** for Age vs Survival\
-   **Value counts** for categorical columns

------------------------------------------------------------------------

## **Example Visualization**

-   Correlation Matrix\
-   Age Distribution by Survival
