🔍 Problem Statement
In educational settings, understanding and improving student performance is a key priority. However, raw academic data often lacks clarity and accessibility for meaningful insights. This project aims to bridge that gap by providing a Python-based solution that allows users to upload a student dataset and automatically generate useful insights, visualizations, and performance categorization.

🧠 Objective
Enable easy uploading of CSV datasets using an interactive method in Google Colab.

Perform data cleaning, analysis, and visualization of student scores.

Categorize students based on performance to support academic planning and intervention.

💻 About the Code
The code is written in Python and optimized to run on Google Colab. Here's a breakdown of its functionality:

📥 CSV File Upload: Users can upload any dataset interactively using Colab’s files.upload() method.

📊 EDA (Exploratory Data Analysis):

Summary statistics

Missing value checks

Distribution of subject-wise scores (math, reading, writing)

📉 Visualizations:

Histograms with KDE

Correlation heatmap

Gender-based boxplots

📈 Performance Categorization:

Calculates the average score across subjects.

Categorizes students into Low, Medium, or High performance levels using score ranges.

⚙️ Enhancements and Problem Tackling
Dynamic Column Detection: Instead of hardcoding columns, the code checks for the presence of score-related columns to ensure compatibility with different datasets.

Interactive File Upload: Eliminated static file paths; now users can upload any .csv file easily without changing the code.

Modular & Readable Structure: The code is divided into clear blocks for uploading, analysis, and visualization—making it beginner-friendly and easy to maintain.

Auto Performance Labeling: Uses pd.cut() to dynamically assign categories, making the output insightful for educators or analysts.

📌 Technologies Used
Python

Pandas

Matplotlib

Seaborn

Google Colab

📂 How to Use
Open the project in Google Colab.

Run the first cell to upload your CSV file.

Execute the next cells to view insights and results.

🙌 Credits
Project by Tarun Singh, B.Tech CSE (AI & ML), KIET Ghaziabad.

Inspired by real-world educational data analytics challenges.


