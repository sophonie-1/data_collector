## Data Analytics Code Challenge

This repository contains a comprehensive data analytics challenge designed as a journey through the joys of data science. The challenge encourages participants to explore a synthetic dataset from multiple angles, uncovering insights that are meaningful and relevant to the broader data science community. Whether you're analyzing trends, performing statistical tests, or applying machine learning techniques, the goal is to transform a seemingly simple dataset into a source of actionable knowledge.

The provided materials include a starter Jupyter notebook and a synthetic dataset (`data1.csv`). All analysis must be conducted within the notebook, using only the given dataset—no external data sources are permitted.

## Key Objectives
 **Data Exploration**: Dive into descriptive statistics, visualizations, and data quality checks.
 **Multi-Angle Analysis**: Approach the data through univariate, bivariate, time-series, clustering, and hypothesis testing lenses.
 **Community-Relevant Insights**: Derive findings that could inform real-world applications, such as customer segmentation or trend forecasting.
 **Reproducibility**: Ensure all code is self-contained and executable in a standard Jupyter environment.

## Getting Started

### Prerequisites
- Python 3.8+ with Jupyter Notebook (or JupyterLab).
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `sklearn`, `statsmodels` (install via `pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels`).

### Installation
1. Clone or download this repository.
2. Navigate to the project directory:
   ```
   cd data-analytics-code-challenge
   ```
3. Create a virtual environment (recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
5. Launch Jupyter:
   ```
   jupyter notebook
   ```

### Project Structure
```
data-analytics-code-challenge/
├── README.md                 # This file
├── requirements.txt          # Python dependencies
├── data1.csv                 # Synthetic dataset (do not modify or replace)
├── bukira_sophonie.ipynb  # Starter notebook for analysis
└── temp_cell.json                   # (Optional) Generated plots and results
```

## Usage

1. **Open the Notebook**: Launch `DataAnalyticsCodeChallenge.ipynb` in Jupyter.
2. **Load the Data**: The notebook includes code to load `data1.csv`. Run the initial cells to inspect the dataset (shape, columns, types, etc.).
3. **Perform Analysis**:
   - Start with data quality checks (missing values, duplicates).
   - Proceed to EDA: Univariate (histograms, bar plots), bivariate (boxplots, correlations), and time-series if applicable.
   - Apply advanced techniques: Clustering (e.g., KMeans), statistical tests (e.g., ANOVA).
   - Document insights in markdown cells, focusing on community relevance (e.g., business implications).
4. **Save Your Work**: Export as `teamname.ipynb` or `surname.ipynb` (per challenge rules). Include all code, outputs, and narratives.
5. **Reproducibility Tip**: Set random seeds (e.g., `np.random.seed(42)`) for consistent results.

### Example Workflow in Notebook
- **Cell 1-2**: Imports and data loading.
- **Cell 3-5**: Quality checks and descriptive stats.
- **Cell 6-10**: Visualizations and correlations.
- **Cell 11-15**: Clustering and statistical tests.
- **Final Section**: Key insights and recommendations.

## Dataset Description
- **File**: `data1.csv`
- **Format**: Comma-separated values (CSV).
- **Size**: Synthetic, compact for quick exploration (~1000 rows assumed).
- **Columns**: Varies; inspect via `df.info()` in the notebook. Example simulated structure includes ID, Date, Category (categorical), Sales (numerical), Region (categorical), Customer_Age (numerical).
- **Theme**: Represents a simple transactional or customer dataset—explore sales patterns, demographics, and trends.

**Important**: Do not use any other dataset. All insights must derive from `data1.csv`.

## Deliverables
- A single Jupyter notebook (`.ipynb`) containing:
  - All code cells with executed outputs.
  - Markdown explanations of methods and insights.
  - Visualizations embedded inline.
- Submit as `teamname.ipynb` or `surname.ipynb`.

## Insights from Sample Analysis
In a simulated run (replace with real data for your submission):
- Sales show right-skewed distribution, indicating high-value outliers.
- Weak negative correlation between age and spending—target younger demographics.
- Three customer clusters: Budget youth, loyal mid-spenders, premium mid-agers.
- No significant regional sales differences (ANOVA p > 0.05).

These highlight how even simple data yields community-valuable strategies, like personalized marketing.

## Contributing
This is a challenge repo—fork and experiment! For questions, open an issue.

## License
MIT License—feel free to adapt for educational purposes.

## Acknowledgments
Inspired by UCU data science exploration best practices. Thanks to the challenge creators for promoting joyful data journeys!

---

*Last Updated: November 14, 2025*