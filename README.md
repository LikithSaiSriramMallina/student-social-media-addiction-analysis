# 📊 Student Social Media Addiction — Data Analysis

> EDA project analyzing screen time, platform usage, and addiction scores among students using Python.

---

## 🔍 Overview

This project performs an **Exploratory Data Analysis (EDA)** on a dataset of students to understand how social media usage affects their daily lives. It examines usage patterns across platforms, genders, and academic levels — and identifies students with high addiction scores.

---

## 📁 Project Structure

```
student-social-media-addiction-analysis/
│
├── Student_Social_Media_Addiction_Analysis.ipynb   # Main analysis notebook
├── Students Social Media Addiction.csv             # Dataset
└── README.md                                       # Project documentation
```

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading, cleaning, manipulation |
| NumPy | Numerical operations |
| Matplotlib | Plotting and visualizations |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive analysis environment |

---

## 📊 Key Analyses Performed

- ✅ Data cleaning — handling missing values and duplicates
- ✅ Summary statistics of the dataset
- ✅ Gender distribution (pie chart)
- ✅ Most used social media platforms (bar chart)
- ✅ Daily usage hours distribution (histogram)
- ✅ Correlation heatmap of numeric variables
- ✅ Average usage hours grouped by gender
- ✅ Student count by academic level
- ✅ Average addiction score by platform
- ✅ Segmentation of high-risk students (addiction score > 7)

---

## 📌 Dataset Features

| Column | Description |
|--------|-------------|
| `Gender` | Student gender |
| `Academic_Level` | Student's current academic level |
| `Most_Used_Platform` | Primary social media platform used |
| `Avg_Daily_Usage_Hours` | Average hours spent on social media per day |
| `Addicted_Score` | Addiction score (numeric scale) |

---

## 💡 Key Insights

- Students spending **more than 5 hours** daily on social media were identified as heavy users
- Students with an **addiction score above 7** were flagged as high-risk
- Platform usage and addiction scores vary significantly across academic levels

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/LikithSaiSriramMallina/student-social-media-addiction-analysis.git
   ```

2. Make sure you have the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Student_Social_Media_Addiction_Analysis.ipynb
   ```

---

## 👤 Author

**Likith Sai Sriram Mallina**  
B.Tech CSE (Data Science) — Aditya College of Engineering & Technology  
📧 srirammallina5@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/srirammallina22) · [GitHub](https://github.com/LikithSaiSriramMallina)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
