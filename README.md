# ⚽ FIFA Dataset - Exploratory Data Analysis

An in-depth exploratory data analysis of FIFA player statistics, performance metrics, and market values.

## 📊 Project Overview

This project analyzes comprehensive FIFA player data to uncover patterns in player performance, market trends, and career progression across different leagues and positions.

## 🛠️ Technologies Used

- **Python** 🐍
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Visualizations
- **Seaborn** - Statistical graphics
- **Plotly** - Interactive charts
- **Jupyter Notebook** - Analysis environment

## 📁 Project Structure

```
├── data/
│   └── fifa_data.csv
├── notebooks/
│   └── fifa_eda.ipynb
├── visualizations/
│   ├── player_stats/
│   ├── market_analysis/
│   └── league_comparison/
├── src/
│   ├── data_loader.py
│   ├── analysis.py
│   └── visualization.py
└── README.md
```

## 🎯 Analysis Focus Areas

### 1. **Player Performance**
- Top players by overall rating
- Position-wise performance analysis
- Age vs Performance correlation
- Player skill distribution

### 2. **Market Analysis**
- Player market value trends
- Top valued players
- Position-wise salary analysis
- Nationality market distribution

### 3. **League Comparison**
- Performance across different leagues
- League-wise player statistics
- Competition strength analysis
- Regional player distribution

### 4. **Career Insights**
- Age progression patterns
- Experience vs Performance
- Player development trajectory
- Potential rating analysis

## 📈 Key Metrics Analyzed

- Overall Rating
- Potential Rating
- Market Value
- Salary
- Player Age
- Position Classification
- Nationality
- Club Information
- Performance Attributes

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

### Running the Analysis
```bash
jupyter notebook notebooks/fifa_eda.ipynb
```

## 📊 Visualizations Included

- Player rating distribution
- Market value heatmaps
- Age vs Performance scatter plots
- League comparison charts
- Position-wise statistics
- Top players ranking
- Nationality distribution
- Career progression curves

## 💡 Key Findings

- Premier insights about player performance
- Market value determinants
- League competitiveness analysis
- Career development patterns
- Regional player strengths

## 🎓 Learning Outcomes

- Real-world data analysis
- Sports analytics fundamentals
- Statistical interpretation
- Data-driven insights
- Presentation skills

## 📝 Analysis Sections

```
1. Data Loading & Overview
2. Data Cleaning & Preprocessing
3. Descriptive Statistics
4. Distribution Analysis
5. Correlation Analysis
6. Performance Trends
7. Market Analysis
8. Comparative Analysis
9. Key Insights & Conclusions
```

## 🔧 Code Example

```python
import pandas as pd
import seaborn as sns

# Load FIFA data
df = pd.read_csv('data/fifa_data.csv')

# Top 10 players
top_players = df.nlargest(10, 'Overall')[['Name', 'Overall', 'Position', 'Club']]
print(top_players)

# Market value by position
sns.boxplot(data=df, x='Position', y='Market Value')
```

## 📄 License

MIT License

## 👤 Author

**Zeeshan Haider**
- GitHub: [@Zeeshanhaider-30](https://github.com/Zeeshanhaider-30)

## 🤝 Contributing

Contributions and suggestions welcome!

---

*FIFA Analytics | 2024*
