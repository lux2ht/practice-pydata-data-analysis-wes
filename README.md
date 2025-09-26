# Python Data Analysis Practice

Data practice notebooks following "Python for Data Analysis, 3rd Edition" by Wes McKinney. This repository contains practical examples and exercises working through the concepts presented in the book.

## Practice Notebooks

The repository includes several Jupyter notebooks that follow different chapters and topics from the book:

1. **Baby Names Analysis** (`baby_name.ipynb`)
   - Working with the US baby names dataset
   - Demonstrates data loading, cleaning, and time series analysis
   - Practice with pandas DataFrame operations
   - Data visualization with matplotlib and seaborn
   - Topics: Data manipulation, grouping, and visualization

2. **Federal Elections Analysis** (`fed_elec.ipynb`)
   - Analysis of campaign finance data
   - Complex data transformations and aggregations
   - Working with categorical and numerical data
   - Topics: Advanced pandas operations and data analysis

3. **USDA Food Database** (`usda.ipynb`)
   - Nutritional data analysis
   - Database-style operations in pandas
   - Data merging and joining
   - Topics: Data relationships and SQL-like operations

4. **Statistical Models** (`models.ipynb`)
   - Statistical analysis and modeling
   - Working with numerical computing in Python
   - Practice with NumPy and statistical functions
   - Topics: Statistical analysis and modeling techniques

5. **General Data Analysis** (`data_analysis.ipynb`)
   - General data analysis techniques
   - Comprehensive examples of data wrangling
   - Various data processing methods
   - Topics: Data cleaning, transformation, and analysis

## Project Structure

```
.
├── datasets/               # Collection of datasets
│   ├── babynames/         # US baby names by year (1880-2010)
│   ├── bitly_usagov/      # Bitly usage data
│   ├── fec/               # Federal Election Commission data
│   ├── haiti/             # Haiti data
│   ├── movielens/         # MovieLens dataset
│   ├── mta_perf/          # MTA performance data
│   ├── titanic/           # Titanic passenger data
│   └── usda_food/         # USDA food database
│
└── examples/              # Example data files for practice
    ├── CSV files
    ├── JSON files
    ├── Excel files
    └── Other data formats
```

## Datasets

The repository contains several datasets for analysis:

1. **Baby Names** (`datasets/babynames/`)
   - US baby name frequencies from 1880-2010
   - Data format: yearly text files with name, gender, and count

2. **Federal Election Commission** (`datasets/fec/`)
   - Campaign finance data

3. **MovieLens** (`datasets/movielens/`)
   - Movie ratings and metadata

4. **USDA Food Database** (`datasets/usda_food/`)
   - Nutritional information for various foods

And more datasets are available in the `datasets` directory.

## Example Files

The `examples` directory contains various data files in different formats for practice:
- CSV files
- JSON files
- Excel spreadsheets
- Time series data
- And more

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/lux2ht/practice-pydata-data-analysis-wes.git
cd practice-pydata-data-analysis-wes
```

2. Set up your Python environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## Book Reference

These practice notebooks follow "Python for Data Analysis, 3rd Edition" by Wes McKinney. The examples and exercises are adapted from and inspired by the book's content, with modifications and additional practice scenarios.