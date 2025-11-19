# ⚡ AEP Energy Consumption Analysis

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive data mining project analyzing hourly energy consumption patterns from American Electric Power (AEP) and building forecasting models.

## 📊 Project Overview

This project performs in-depth analysis of AEP's hourly energy consumption data from 2004-2018, identifying patterns, trends, and developing predictive models for energy demand forecasting.

## 🎯 Key Features

- **Data Exploration & Statistical Analysis** - Comprehensive EDA with 121,273 hourly records
- **Time Series Decomposition** - Seasonal, trend, and residual analysis
- **Pattern Recognition** - Hourly, daily, monthly, and seasonal consumption patterns
- **Machine Learning Forecasting** - Prophet model implementation for energy demand prediction
- **Advanced Visualization** - Professional plots and insights generation

## 📈 Dataset

- **Source**: American Electric Power (AEP) hourly consumption data
- **Period**: 2004-2018
- **Records**: 121,273 hourly observations
- **Features**: 
  - `Datetime`: Hourly timestamps
  - `AEP_MW`: Energy consumption in Megawatts

## 🛠️ Installation & Usage

### Prerequisites
```bash
Python 3.7+
Jupyter Notebook

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
pip install prophet scikit-learn statsmodels
```

### Run the Project
```bash
git clone https://github.com/yourusername/aep-energy-analysis.git
cd aep-energy-analysis
jupyter notebook
```
Open `AEP_Energy_Analysis.ipynb` and run all cells.

## 📁 Project Structure

```
aep-energy-analysis/
│
├── AEP_Energy_Analysis.ipynb      # Main analysis notebook
├── AEP_hourly.csv                 # Dataset (not included in repo)
├── images/                        # Generated visualizations
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies
```

## 🔬 Methodology

### 1. Data Preprocessing
- DateTime conversion and indexing
- Handling missing values
- Data quality validation

### 2. Statistical Analysis
- Central tendency measures (Mean: 15,500 MW)
- Dispersion analysis (Range: 9,581-25,695 MW)
- Distribution analysis (Skewness: 0.379)

### 3. Feature Engineering
- Time-based features (year, month, hour, season)
- Weekend/holiday indicators
- Rolling statistics

### 4. Pattern Analysis
- Seasonal consumption patterns
- Hourly demand cycles
- Yearly trends and anomalies

### 5. Forecasting
- Facebook Prophet model implementation
- Train-test split (80-20)
- 365-day future predictions

## 📊 Key Findings

### Consumption Patterns
- **Peak Hours**: 6-8 PM daily
- **Seasonal Highs**: Summer months (June-August)
- **Weekly Pattern**: Higher consumption on weekdays
- **Yearly Trend**: Gradual increase over time

### Statistical Insights
- Average consumption: 15,499.51 MW
- Standard deviation: 2,591.40 MW
- Right-skewed distribution (positive skew)
- Relatively stable consumption patterns

## 🎨 Visualizations

The project includes comprehensive visualizations:
- Time series plots
- Seasonal decomposition
- Hourly consumption patterns
- Monthly averages
- Forecasting results
- Model performance metrics

## 🚀 Results

The Prophet model successfully:
- Captures seasonal patterns
- Identifies trend components
- Provides reliable 365-day forecasts
- Handles holidays and special events

## 🔮 Future Enhancements

- [ ] Compare multiple forecasting models (ARIMA, LSTM)
- [ ] Incorporate external factors (temperature, holidays)
- [ ] Real-time prediction dashboard
- [ ] Anomaly detection system
- [ ] API deployment for predictions

## 👥 Contributors

- **Erfan Nahidi** - Data Mining Project
- **Class**: Saturday 10:30

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Acknowledgments

- American Electric Power for the dataset
- Facebook Research for Prophet library
- Python data science community

---

**⭐ If you find this project useful, please give it a star!**
```

This README includes:
- Professional badges and formatting
- Clear installation instructions
- Comprehensive project structure
- Detailed methodology
- Key findings and results
- Future enhancement ideas
- Professional acknowledgments

It's ready to be used on GitHub and will give visitors a complete understanding of your project! 🚀
