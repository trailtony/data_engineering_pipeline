# Data Engineering Pipeline

This project demonstrates a step-by-step approach to wrangle and tidy data from SQLite tables using pandas in a Jupyter notebook.

## Prerequisites

- Python 3.8 or higher
- [pip](https://pip.pypa.io/en/stable/)
- [Jupyter Notebook](https://jupyter.org/install)
- The following Python packages:
  - pandas
  - sqlite3 (included in Python standard library)

## Setup

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd data_engineering_pipeline

2. **Install dependencies:**
- pip install pandas jupyter

3. **Ensure the SQLite database file is present:**

The notebook expects cademycode.db in the project root.
Running the Notebook
Start Jupyter Notebook:

Open main.ipynb in the Jupyter interface.

Run all cells to execute the data wrangling pipeline.

Output
Cleaned CSV files will be generated:
cleaned_students.csv
cleaned_courses.csv
cleaned_student_jobs.csv
cleaned_full_data.csv (if merged data is created)
License
See LICENSE for details. ``````