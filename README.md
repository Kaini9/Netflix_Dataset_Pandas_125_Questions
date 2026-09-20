# Netflix Dataset — Pandas 125 Questions

A practical Pandas exercise workbook containing solutions to **125 data analysis questions** using a Netflix titles dataset.

This project was completed in **Google Colab** and is designed for beginners who want to practice data loading, selection, filtering, sorting, updating, grouping, and data cleaning with Pandas.

## Repository Contents

- `netflix_125_question_workbook.ipynb` — Google Colab/Jupyter Notebook containing the questions and Pandas solutions.
- `README.md` — Project documentation.

## Dataset

The workbook uses a Netflix titles dataset with information about movies and TV shows.

The main columns include:

- `show_id`
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `genres`
- `description`

## Topics Covered

The notebook contains 125 questions divided into the following sections:

| Section | Topic | Questions |
|---------|-------|-----------|
| A | First Analysis of Data | 15 |
| B | Selection with `[]`, `.loc`, and `.iloc` | 25 |
| C | Conditions with `.loc` | 20 |
| D | Sorting | 10 |
| E | Updating Data | 15 |
| F | GroupBy | 20 |
| G | Cleaning Data | 20 |
| **Total** |  | **125** |

## Google Colab

This project was completed and executed in **Google Colab**.

Open the notebook directly in Google Colab:

[Open Netflix Pandas Workbook in Google Colab](https://colab.research.google.com/github/Kaini9/Netflix_Dataset_Pandas_125_Questions/blob/main/netflix_125_question_workbook.ipynb)

Google Colab provides a cloud-based Python environment, so you do not need to install Python or Jupyter Notebook locally.

## How to Run in Google Colab

1. Open the notebook using the Google Colab link above.
2. Upload the Netflix CSV dataset when prompted, or update the file path in the notebook.
3. Run the cells from top to bottom.
4. Review the output for each question.

Example file-loading code:

```python
import pandas as pd

df = pd.read_csv("/content/NetFlix.csv")
df.head()
```

## Skills Practiced

By completing this workbook, you will practice:

- Loading CSV files with Pandas
- Inspecting DataFrames
- Understanding rows and columns
- Selecting data with brackets
- Using `.loc` and `.iloc`
- Filtering rows using conditions
- Sorting data
- Updating column values
- Handling missing values
- Grouping data with `groupby()`
- Calculating counts and averages
- Working with string values
- Cleaning and transforming columns
- Performing exploratory data analysis

## Learning Objective

The goal of this project is to build a strong foundation in Pandas and data analysis by solving realistic questions using a Netflix dataset.

All solutions use Pandas operations instead of manual counting.

## Author

- Workbook prepared by **Ananda Rimal**
- Solutions completed by **Saval Kaini**

## License

This project is intended for educational and practice purposes.
