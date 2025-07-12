# 🚀 Employee Performance Analysis System

A powerful, interactive system that delivers deep insights into employee performance through advanced data analytics, machine learning, and visualizations.

## 📦 Overview

This system helps HR teams, department managers, and executives to:
- Track and analyze employee performance
- Segment employees using machine learning
- Forecast future performance
- Generate visual reports and dashboards

## ✅ Key Features

### 🔍 Core Analysis
- 📈 Statistical Insights
- 🧠 Machine Learning Clustering
- 🤖 Predictive Modeling
- 📊 Trend & Time-Series Analysis
- 🎯 Goal Tracking & Success Rate

### 🎯 Metrics Tracked
- Performance Scores (e.g., productivity, teamwork)
- Operational Data (projects completed, overtime)
- Organizational Info (department, tenure, position)
- Goals & Achievements

## 📁 Project Structure

```
.
├── dashboard_app.py
├── data_generator.py
├── performance_analyzer.py
├── report_generator.py
├── employee_data.csv
├── monthly_performance.csv
├── employee_goals.csv
├── requirements.txt
├── runtime.txt
└── README.md
```

## 🚀 Quick Start

```bash
pip install -r requirements.txt
python data_generator.py
streamlit run dashboard_app.py
```

## 📊 Dashboard Features

- Main Dashboard (key metrics, histograms, heatmaps)
- Department Analysis
- Clustering (K-means, PCA)
- Predictive Modeling (Random Forest)
- Goal Tracking
- Time-Series Performance Trends

## 📤 Excel Report

```bash
python report_generator.py
```

## 💻 Programmatic Use

```python
from performance_analyzer import EmployeePerformanceAnalyzer
analyzer = EmployeePerformanceAnalyzer()
analyzer.load_data('employee_data.csv', 'monthly_performance.csv', 'employee_goals.csv')
analyzer.generate_comprehensive_report()
```

## 🌍 Deployment (Render)

- Ensure `runtime.txt` contains `python-3.11.8`
- Use:
  - Build: `pip install -r requirements.txt`
  - Start: `streamlit run dashboard_app.py --server.port=$PORT --server.address=0.0.0.0`

## 🧠 Analysis Capabilities

- Descriptive & Inferential Stats
- Clustering + Dimensionality Reduction
- Feature Importance Analysis
- Forecasting & Volatility Detection

## 📈 Use Cases

- HR Analytics & Training Needs
- Departmental Resource Planning
- Executive Strategic Insights

## 📬 Support

- Read inline docstrings
- Explore Streamlit UI
- GitHub Issues for bugs/feedback

## 📝 License

MIT License

---

**Transform raw workforce data into powerful insights!**
