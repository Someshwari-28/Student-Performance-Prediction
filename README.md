# Student Performance Prediction Using Machine Learning

# Project Overview

This is a Machine Learning mini project from MNR University. It uses a Random Forest Classifier to predict student performance and identify students who may need additional academic support.

The project classifies students into two categories:

- Pass: G3 >= 10
- Needs Support: G3 < 10

# Dataset Details

- Dataset: UCI Student Performance – Mathematics ("student-mat.csv")
- Total Records: 395 students
- Total Attributes: 33
- Source: UCI Machine Learning Repository

# Algorithm Used

Random Forest Classifier

- Number of trees: 200
- Model A: Uses background and behavioural features without G1 and G2 for early-warning prediction.
- Model B: Includes G1 and G2 as a comparison model.

# Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

# Project Files

- "student_performance.py" – Python implementation.
- "Project_Report.docx" – Project report.
- "requirements.txt" – Required Python libraries.
- "DATASET_LINK.txt" – Dataset download instructions.
- "student-mat.csv" – Dataset (download separately).
- "figures/" – Folder for generated graphs.
- "Project_Presentation.pptx" – Project presentation.
- "Demo_Video" – Project demonstration video or link.

# Installation and Setup

## Step 1: Install Python 3

Download and install Python 3 on your computer.

## Step 2: Download the Dataset

Download the Mathematics dataset from the [UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)

## Step 3: Install Required Libraries

Open the terminal in the project folder and run:

`pip install -r requirements.txt`

## Step 4: Run the Python Program

`python student_performance.py`

The program prints dataset information and model evaluation results. It also generates graph images in the "figures/" folder and saves "results.json".

# MODEL PERFORMANCE RESULTS

According to the project report, **Model A** achieved 72.15% test accuracy and 69.37% mean 5-fold cross-validation accuracy. **Model A** uses background and behavioural features without including previous-period grades (G1 and G2), making it suitable for early-warning prediction.

**Model B** achieved 91.14% test accuracy and 91.39% mean 5-fold cross-validation accuracy. **Model B** includes previous-period grades (G1 and G2), which improves its prediction accuracy.

The results show that **Model B** achieved higher accuracy than **Model A**. However, **Model A** is considered the early-warning model because it predicts student performance without using previous-period grades.

# Team Members

1.Nandini Nagadapally – 25RBAIM0070

2.Sukanya Devi Rayapati – 25RBAIM0074

3.Someshwari Thogarpally – 25RBAIM0075

4.Sahitya Chamanthula – 25RBAIM0077

# Institution Details

**Department:** Computer Science and Engineering (AI & ML)

**University:** MNR University

**Academic Year:** 2026–2027

**Faculty Guide:** Dr. M. Praveen

# Conclusion

This project demonstrates how Machine Learning can be used to predict student academic performance. The Random Forest Classifier helps identify students who may need additional academic support. The early-warning model can help educators take timely action to improve student performance.
