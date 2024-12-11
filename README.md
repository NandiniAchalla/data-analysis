Internet Usage Session Analysis
This project analyzes a dataset of internet usage sessions, exploring user behaviors and session terminations. It leverages Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, analysis, and visualization.

Key Features:

1.Data Cleaning & Preprocessing:

* Convert start_time and usage_time into appropriate formats.
* Handle missing values and correct data types (e.g., upload, download as numeric values).

2.Exploratory Data Analysis (EDA):

* Calculate summary statistics for upload, download, and total data transfer.
* Group data by user and session break reason.

3.Data Visualization:

* Bar Plots for total uploads/downloads by user.
* Box Plots for distribution of upload values.
* Scatter Plots for relationships between upload and download speeds.
* Pie Charts and Count Plots for session break reasons.
* Heatmaps for correlation between variables.

4.Technologies Used:
* Pandas: Data manipulation and analysis.
* NumPy: Numerical data handling.
* Matplotlib & Seaborn: Data visualization.

5.Insights:
* Identified user behavior and peak usage times.
* Analyzed session break reasons to understand common causes for session terminations.
Setup:
* Clone the repository:
* git clone https://github.com/NandiniAchalla/data-analysis.git
* Install required dependencies:
* pip install -r requirements.txt
* Run the Jupyter notebook for analysis:
* jupyter notebook analysis.ipynb
