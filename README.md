# Netflix Data Analysis 🎬📊

This project is an Exploratory Data Analysis (EDA) conducted using Python and Pandas libraries. Serving as an introduction to the world of data science and analytics, this project applies fundamental data cleaning, manipulation, and visualization techniques to raw datasets.

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas (Data Processing & Cleaning), Matplotlib (Data Visualization)
* **Environment:** Google Colab

## 🔍 What Was Done in This Project?
* **Data Cleaning:** Text data (" min") in the duration column was extracted and converted into a numerical (`float`) format suitable for mathematical operations. Handled missing (NaN) values to prevent them from skewing the analysis.
* **Data Filtering & Querying:** Content was filtered using multiple conditions based on type (Movie/TV Show), country, and release year.
* **Aggregations:** Average values for specific metrics (e.g., US movies) were calculated using the `.mean()` function.
* **Visualization:** Bar charts showing content production trends over time were created using Matplotlib.

## 💡 Key Insights
1. **Average Content Duration:** The average duration of US-made Netflix movies was found to be **90.63 minutes**.
2. **Production Peak:** Analyzing the timeline from 1990 to the present, a massive surge (peak) in Netflix's content volume was clearly observed, especially between **2016 and 2020**.

## 🚀 How to Run the Project
1. Download the `netflix.ipynb` file or open it directly in Google Colab.
2. Upload the Netflix dataset (in CSV format) obtained from Kaggle or the relevant source to your working directory.
3. Run the cells in the notebook sequentially to view all analysis steps and visualizations.
