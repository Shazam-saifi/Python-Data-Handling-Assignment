# Python Data Handling and Preprocessing with Pandas

## Project Overview

This project demonstrates data handling, preprocessing, database integration, visualization, object-oriented programming, and unit testing using Python. The objective is to identify the best-fitting ideal functions for a given set of training functions using the Least Squares Method and then map test data to those selected ideal functions.

The project has been developed using Python and follows a modular, object-oriented design while utilizing SQLite for data storage and Bokeh for interactive visualization.

---

## Features

- Load and validate CSV datasets

- Store datasets in a SQLite database

- Select the best ideal function for each training function using the Least Squares Method (Sum of Squared Errors)

- Map test data to the selected ideal functions using the specified maximum deviation rule

- Interactive visualization using Bokeh

- Object-oriented implementation

- Custom exception handling

- Unit testing for validation

---

## Technologies Used

- Python 3.14

- Pandas

- NumPy

- SQLAlchemy

- SQLite

- Bokeh

- Matplotlib

- Jupyter Notebook

- Git & GitHub

---

## Project Structure

```

Python-Data-Handling-Assignment/

│

├── Data/

│   ├── train.csv

│   ├── test.csv

│   └── ideal.csv

│

├── Data Handling and Preprocessing with Pandas.ipynb

├── requirements.txt

├── .gitignore

└── README.md

```

---

## Dataset Description

The project uses three datasets:

### train.csv

Contains the training data with one x column and multiple training functions.

### ideal.csv

Contains one x column and multiple ideal functions used to determine the closest match.

### test.csv

Contains test points that are assigned to one of the selected ideal functions.

---

## Project Workflow

1. Import required libraries.

2. Load datasets using Pandas.

3. Validate dataset availability.

4. Store datasets in a SQLite database.

5. Calculate the Sum of Squared Errors (SSE) between each training function and every ideal function.

6. Select the best ideal function for each training function.

7. Map test data to the selected ideal functions using the assignment's deviation criteria.

8. Store the mapping results.

9. Generate interactive visualizations with Bokeh.

10. Validate the implementation through unit tests.

---

## Database

A SQLite database named:

```

python_assignment.db

```

is automatically created during execution.

The database contains:

- training_data

- ideal_functions

- test_data

- mapped_results (generated after mapping)

---

## Installation

Clone the repository:

```bash

git clone https://github.com/Shazam-saifi/Python-Data-Handling-Assignment.git

```

Navigate to the project directory:

```bash

cd Python-Data-Handling-Assignment

```

Install the required packages:

```bash

pip install -r requirements.txt

```

---

## Running the Project

Launch Jupyter Notebook:

```bash

jupyter notebook

```

Open:

```

Data Handling and Preprocessing with Pandas.ipynb

```

Run all notebook cells sequentially.

---

## Output

The project generates:

- SQLite database

- Best ideal function selection

- Test point mapping

- Interactive Bokeh visualizations

- Unit test results

---

## Learning Outcomes

This project demonstrates practical experience in:

- Data preprocessing using Pandas

- Numerical analysis using Least Squares

- SQLite database integration

- Object-Oriented Programming (OOP)

- Exception handling

- Interactive visualization

- Software testing

- Version control with Git and GitHub
