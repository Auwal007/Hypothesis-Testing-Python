# Hypothesis Testing in Python: Gender Analysis of International Soccer Goals

A comprehensive statistical analysis comparing goal-scoring patterns between men's and women's international soccer matches using Python and hypothesis testing. This project is based on a DataCamp hypothesis testing exercise with real-world soccer data analysis.

## 📊 Project Overview

This DataCamp-inspired project investigates whether more goals are scored in women's international soccer matches compared to men's matches through rigorous statistical hypothesis testing. The analysis focuses on official FIFA World Cup matches since 2002 to ensure data consistency and relevance.

### 🎯 Research Question
**"Are more goals scored in women's international soccer matches than men's?"**

### 📈 Hypothesis
- **Null Hypothesis (H₀)**: The mean number of goals scored in women's international soccer matches is the same as men's
- **Alternative Hypothesis (H₁)**: The mean number of goals scored in women's international soccer matches is greater than men's
- **Significance Level**: α = 0.10 (10%)

## 📁 Project Structure

```
Hypothesis-Testing-Python/
├── data/
│   ├── men_results.csv          # Men's international soccer match results
│   ├── women_results.csv        # Women's international soccer match results
│   └── soccer-pitch.jpg         # Visual asset
├── Hypothesis testing/
│   ├── 1.ipynb                  # Hypothesis testing notebook 1
│   └── 2.ipynb                  # Hypothesis testing notebook 2
├── notebook (2).ipynb           # Main analysis notebook
└── README.md                    # Project documentation
```

## 📊 Dataset Information

### Men's Results Dataset
- **Records**: 44,355 matches
- **Time Period**: 1872-2023
- **Features**: Date, Home Team, Away Team, Home Score, Away Score, Tournament

### Women's Results Dataset
- **Records**: 4,886 matches
- **Time Period**: 1969-2023
- **Features**: Date, Home Team, Away Team, Home Score, Away Score, Tournament

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib/Seaborn** - Data visualization
- **SciPy** - Statistical testing
- **Jupyter Notebook** - Interactive development environment

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Running the Analysis
1. Clone the repository:
```bash
git clone https://github.com/Auwal007/Hypothesis-Testing-Python.git
cd Hypothesis-Testing-Python
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open and run the main analysis notebook: `notebook (2).ipynb`

## 📋 Analysis Workflow

1. **Data Loading & Exploration**
   - Load men's and women's soccer match datasets
   - Explore data structure and quality
   - Filter data for FIFA World Cup matches since 2002

2. **Data Preprocessing**
   - Calculate total goals per match
   - Filter relevant tournaments and date ranges
   - Handle missing values and outliers

3. **Exploratory Data Analysis**
   - Descriptive statistics comparison
   - Data visualization and distribution analysis
   - Identify patterns and trends

4. **Hypothesis Testing**
   - Assumption testing (normality, independence)
   - Statistical test selection and execution
   - P-value calculation and interpretation

5. **Results & Conclusion**
   - Statistical significance evaluation
   - Business implications
   - Recommendations for further research

## 📊 Key Findings

### Statistical Test Results
- **Test Used**: Mann-Whitney U test (non-parametric alternative to t-test)
- **P-value**: 0.0051 (0.51%)
- **Significance Level**: α = 0.10 (10%)
- **Decision**: **Reject the null hypothesis**

### 🏆 Conclusion
**Women score significantly more goals than men in international soccer matches!**

The statistical analysis provides strong evidence (p-value = 0.0051 < α = 0.10) to reject the null hypothesis. This means we can conclude with 90% confidence that women's international soccer matches have a significantly higher mean number of goals scored compared to men's matches.

### Business Impact
This finding supports the sports journalist's initial hypothesis and provides statistical backing for an investigative article that could engage subscribers interested in soccer analytics and gender-based performance comparisons in sports.

## 🔍 Statistical Methods Used

- **Primary Test**: Mann-Whitney U test (non-parametric test chosen due to non-normal data distribution)
- **Descriptive Statistics**: Mean, median, standard deviation comparison
- **Assumption Testing**: Data normality assessment using histograms and Q-Q plots  
- **Alternative Considered**: Two-sample t-test (ruled out due to non-normal distribution)
- **Visualization**: Histograms with KDE, Q-Q plots for normality assessment

## 📈 Visualizations

The project includes various visualizations to support the analysis:
- Goal distribution comparisons
- Box plots showing central tendencies
- Histogram overlays for visual hypothesis testing
- Time series analysis of goal-scoring trends

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

[**Muhammad Adam**]([LICENSE](https://x.com/M0hammadAI))

## 📚 References

- DataCamp Hypothesis Testing in Python course materials
- Data sourced from reliable international soccer databases
- Statistical methods based on standard non-parametric hypothesis testing procedures
- FIFA World Cup official match records

## 🏆 Acknowledgments

- DataCamp for the project framework and methodology
- International soccer governing bodies for match data
- Open-source Python community for statistical tools (SciPy, pandas, matplotlib)
- Sports analytics community for methodology guidance

---

*This DataCamp-based project demonstrates the application of statistical hypothesis testing in sports analytics, providing insights into gender-based performance patterns in international soccer. The analysis successfully identified a statistically significant difference in goal-scoring patterns between men's and women's international matches.*