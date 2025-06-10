# 📊 Pearson Correlation Analysis: Social Media Usage vs Productivity

This repository contains a statistical analysis of the relationship between **daily social media usage** and **self-rated productivity** among university students. The analysis applies **Pearson’s correlation coefficient (r)** to measure the strength and direction of the linear relationship between the two variables.

## 📁 Project Structure

project-root/
├── data/                       # Dataset folder
│   └── survey_results.csv      # Raw data collected from participants
│
├── visuals/                    # Output visualizations
│   └── correlation_plots.png   # Scatter plot, histograms, and heatmap
│
├── pearson_analysis.ipynb      # Main Jupyter Notebook for Pearson correlation analysis
├── requirements.txt            # Python dependencies
└── README.md                   # Project overview and documentation

## 🧪 Objective

To determine whether there is a **statistically significant correlation** between the number of hours students spend on social media per day and their **self-assessed productivity levels**.

## 🧠 Methods

- **Pearson Correlation Test** to examine the linear relationship
- **Data visualization** using:
  - Scatter plot with regression line
  - Histogram of social media usage and productivity
  - Heatmap of correlation matrix
- **Normality check** using histogram and visual inspection

## 📉 Key Findings

- Pearson’s r = `-0.1364`, indicating a **very weak negative correlation** between social media usage and productivity.
- p-value = `0.1759` (> 0.05), suggesting the relationship is **not statistically significant**.
- Distribution of social media use is slightly **positively skewed**, while productivity scores are nearly **normal**.

## 📷 Visualizations

You can find key visualizations in the [`visuals/`](./visuals/) folder:
- Scatter plot with regression line
- Histograms
- Correlation heatmap

## 📦 Requirements

Install dependencies via pip:

```bash
pip install -r requirements.txt
🔍 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Open the Jupyter notebook:

bash
Copy
Edit
jupyter notebook pearson_analysis.ipynb
✍️ Author
Miftahuddin S. Arsyad

Undergraduate Student, Informatics Engineering – Universitas Sam Ratulangi

Research: [Social Media Impact on Academic Productivity]

📚 Citation
If you use this repo or findings for academic purposes, please cite:

scss
Copy
Edit
Arsyad, M. S. (2025). The Correlation between Social Media Usage and Productivity Among University Students. [Unpublished undergraduate research].
