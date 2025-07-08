# Automated Review Rating System

## Overview
This is an automated review rating system that analyzes Amazon Fine Foods Review data from Kaggle. The project performs comprehensive exploratory data analysis (EDA) and builds predictive models to automatically classify and rate product reviews based on customer feedback patterns and sentiment.

## Features
- **Data Exploration**: Comprehensive analysis of review data including shape, structure, and statistical summaries
- **Data Cleaning**: Handles missing values and duplicate entries
- **Rating Analysis**: Analyzes score distributions and patterns
- **Review Filtering**: Advanced filtering capabilities based on scores and helpfulness metrics
- **Data Visualization**: Visual representations of rating distributions and trends

## Project Structure
```
├── README.md              # Project documentation
├── requirements.txt       # Python dependencies
├── data/
│   └── Reviews.csv       # Source review dataset
├── notebooks/
│   └── main.ipynb        # Main analysis notebook
├── app/                  # Application code
├── frontend/             # Frontend components
└── models/              # Data models and ML components
```

## Dataset
The project analyzes the Amazon Fine Foods Review dataset from Kaggle (`Reviews.csv`) containing the following key features:
- **Score**: Product ratings (1-5 scale)
- **Summary**: Review summary text
- **HelpfulnessNumerator**: Number of helpful votes
- **ProfileName**: Reviewer profile name
- **ProductId**: Product identifier
- **UserId**: User identifier
- **Time**: Review timestamp

## Analysis Highlights
The notebook performs several key analyses:

1. **Data Quality Assessment**
   - Shape and structure analysis
   - Missing value detection and handling
   - Duplicate record identification

2. **Exploratory Data Analysis**
   - Statistical summaries of numerical features
   - Score distribution visualization
   - High-rated product identification

3. **Advanced Filtering**
   - Products with scores > 4
   - Reviews with high helpfulness scores
   - Combined filtering for quality reviews

4. **Data Visualization**
   - Score distribution bar charts
   - Rating patterns analysis

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required Python packages (see requirements.txt)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `notebooks/main.ipynb` to explore the analysis

### Required Packages
```python
numpy
pandas
matplotlib
seaborn
```

## Usage
1. Ensure the `Reviews.csv` file is placed in the `data/` directory
2. Run the notebook cells sequentially to perform the complete analysis
3. Modify filtering criteria and visualization parameters as needed
4. Explore different aspects of the review data

## Key Insights
- Analysis of product rating distributions
- Identification of highly-rated products and helpful reviews
- Data quality assessment and cleaning procedures
- Statistical overview of review patterns

## Contributing
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
For questions or suggestions, please open an issue in the repository.

---
*Last updated: July 2025*