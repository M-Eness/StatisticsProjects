# 🎓 Student Academic Performance Analysis

This project is a comprehensive data analysis study that investigates the factors influencing student academic performance. Developed in a **Jupyter Notebook** using Python, the project includes a full pipeline from data cleaning and statistical analysis to data visualization.

---

## 🎯 Project Goal

The primary objective is to scientifically analyze the impact of key variables like **hours studied**, **tutoring**, **region**, and **parental education level** on students' **exam scores**. The analysis specifically focuses on how a student's study habits relate to their academic results.

---

## 🛠️ Tools and Libraries

-   **Language**: Python
-   **Libraries**:
    -   `pandas`: For data manipulation and analysis.
    -   `numpy`: For numerical operations and scientific computing.
    -   `matplotlib.pyplot`: For creating static, animated, and interactive visualizations.
    -   `seaborn`: For creating informative and attractive statistical graphics.
    -   `scipy.stats`: For statistical analysis and hypothesis testing.

---

## 📁 Dataset

The analysis uses the `SAP-4000.csv` dataset, which contains data for 4,000 students across seven features:

-   **Gender**: The student's gender.
-   **HoursStudied/Week**: The number of hours the student studies per week.
-   **Tutoring**: Whether the student receives private tutoring.
-   **Region**: The student's residential area (Urban/Rural).
-   **Attendance(%)**: The student's attendance percentage.
-   **Parent Education**: The education level of the student's parents. This column initially contained missing values (`NaN`) that were cleaned before analysis.
-   **Exam_Score**: The student's final exam score.

---

## 🔬 Methodology and Findings

The project employs **descriptive statistics** and **hypothesis testing** to draw conclusions from the data.

### Descriptive Statistics
Key descriptive statistics, such as mean, median, variance, and standard deviation, were calculated for the `HoursStudied/Week` variable. The Interquartile Range (IQR) method was used to confirm that the dataset does not contain any significant outliers.

### Hypothesis Testing (T-Test)
A **one-sample t-test** was performed to determine if there is a statistically significant relationship between exam scores and study hours.
-   **Null Hypothesis (H₀)**: The mean weekly study hours is 9.5.
-   **Alternative Hypothesis (H₁)**: The mean weekly study hours is greater than 9.5.

The test results led to the rejection of the null hypothesis. This finding indicates that the average weekly study hours for students in this dataset is **statistically greater than 9.5 hours**.

---

## 🚀 How to Run

1.  Ensure you have the required Python libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`) installed in your environment.
2.  Place the `StudentAcademicPerformance.ipynb` and `SAP-4000.csv` files in the same directory.
3.  Open the notebook using Jupyter Notebook or JupyterLab and run the cells sequentially to reproduce the analysis.
