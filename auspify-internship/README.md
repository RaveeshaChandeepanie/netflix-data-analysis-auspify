# Netflix Data Analysis: Auspify Internship

**Intern:** Raveesha Chandeepanie
**Program:** Data Analysis Using Python (4-Week Internship), Auspify Technologies

## Tasks Completed
| Task | Title | Status |
|------|-------|--------|
| 1 | Netflix Data Cleaning & Preparation | Completed |

## Task 1: Netflix Data Cleaning & Preparation

**Objective:** Prepare and organize the Netflix dataset for business analytics and reporting.

**What was done:**
- Imported the dataset (8,790 records, 10 columns) using Python and Pandas
- Found hidden missing values: the text "Not Given" was used as a placeholder in the `country` and `director` columns
- Converted the placeholders to real missing values and filled them with "Unknown"
- Removed duplicate records and extra whitespace
- Standardized columns:
  - `type`: consistent capitalization (Movie / TV Show)
  - `date_added`: converted to datetime, with a new `year_added` column
  - `duration`: split into `duration_value` and `duration_unit`
  - `rating`: grouped into audience categories (Kids, Teens, Adults, Unrated)
- Exported the cleaned dataset as `netflix_clean.csv`

## Tools Used
Python, Pandas, NumPy, Jupyter Notebook

## Folder Structure
All project files are inside the `auspify-internship/` folder:
- `data/`: raw dataset (`Dataset.csv`)
- `notebooks/`: Jupyter notebook for each task
- `outputs/`: cleaned dataset (`netflix_clean.csv`)
- `screenshots/`: screenshots of completed tasks

## Next Tasks
Tasks 2, 3 and 4 will be added to this repository as they are completed.

#Auspify #AuspifyTechnologies #AuspifyInternship #AuspifyProjects
