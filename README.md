# Python Data Analysis Practice

Collection of Jupyter notebooks and example data used to practice concepts from "Python for Data Analysis, 3rd Edition" by Wes McKinney. The repository contains notebooks that explore real datasets and demonstrate common data analysis workflows using pandas, NumPy, and visualization libraries.

## Repository layout

- `datasets/` — raw datasets used by the notebooks (babynames, fec, usda_food, movielens, etc.)
- `examples/` — small example files (CSV/JSON/Excel) used for short exercises and demonstrations
- `practice/` — Jupyter notebooks and additional practice files

## Practice Notebooks

The `practice/` folder contains a number of notebooks and supporting files. Key notebooks include:

- `baby_name.ipynb` — Baby names analysis (US baby names by year)
- `fed_elec.ipynb` — Federal Elections Analysis (campaign finance data)
- `usda.ipynb` — USDA food database analysis (nutritional data)
- `models.ipynb` — Statistical models and numerical analysis
- `data_analysis.ipynb` — General data analysis examples and exercises
- `pandas_prac.ipynb` — pandas-focused practice examples
- `plotting.ipynb` — Visualization examples (matplotlib, seaborn)
- `time_series_prac.ipynb` — Time series practice and analysis
- `Numpy_prac.ipynb` — NumPy practice and array operations
- Other notebooks and supporting files: `build_in_prac.ipynb`, `data wrangling.ipynb`, `data_cleaning.ipynb`, `data_group_prac.ipynb`, `modeling.ipynb`, `prac.ipynb`, `read_write_files.ipynb`.

Additional files in `practice/` include example spreadsheets and binary arrays used by the notebooks:
- `ex2.xlsx`, `ex2_2.xlsx`, `array_archive.npz`, `array_compreseed.npz`, `some_array.npy`, `mydata.sqlite`, and a few text files.

## Datasets

Datasets used across the notebooks live in the `datasets/` directory. Notable datasets:

- `datasets/babynames/` — US baby name frequencies (1880–2010)
- `datasets/fec/` — Federal Election Commission campaign finance data
- `datasets/usda_food/` — USDA food and nutrition data
- `datasets/movielens/` — MovieLens ratings and metadata
- `datasets/mta_perf/`, `datasets/titanic/`, and other smaller datasets used for practice

If you plan to re-run notebooks, make sure the `datasets/` folder remains in the repository, and paths inside the notebooks are correct (many notebooks reference relative paths such as `./datasets/fec/...`).

## Getting started

1. Clone the repository

```bash
git clone https://github.com/lux2ht/practice-pydata-data-analysis-wes.git
cd practice-pydata-data-analysis-wes
```

2. Create and activate a Python virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

3. Install the typical data science dependencies (adjust to your Python version)

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks in the `practice/` folder to explore the examples.

## Requirements

- Python 3.8+ recommended
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

(Optionally install scikit-learn, statsmodels, or other libraries depending on which notebooks you want to run.)

## Notes and Conventions

- Notebooks are intended for learning and experimentation; some cells are exploratory and may assume datasets are present in `datasets/`.
- Paths in notebooks are relative; if you move notebooks, update the dataset paths accordingly.

## Changelog

- 2025-09-26: Fixed a syntax issue in `practice/fed_elec.ipynb` (corrected import statements in the first code cell). This update is reflected in the "Federal Elections Analysis" notebook entry above.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.