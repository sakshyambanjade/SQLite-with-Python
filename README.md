# SQLite Data Analysis with Python

This project demonstrates a basic but complete workflow of working with SQLite databases using Python. It includes data creation, insertion, querying, and simple data visualization using popular Python libraries like Pandas, Matplotlib, and Seaborn.

## Project Overview

The goal of this project is to:
- Connect to a SQLite database.
- Create a sample user table.
- Insert sample user data.
- Perform SQL queries using `pandas.read_sql`.
- Analyze data (e.g., average age, city-wise customer count).
- Visualize data with a bar chart.

## Tools & Libraries

- Python 3
- SQLite3
- Pandas
- Matplotlib
- Seaborn

## Key Functionalities

1. **Database Setup**
   - Creates a SQLite database and a `users` table if it doesn’t exist.

2. **Data Insertion**
   - Inserts a few sample records into the database.

3. **Data Retrieval and Analysis**
   - Retrieves all user data.
   - Filters users based on spending.
   - Calculates the average age of users.
   - Counts users by city.
   - Aggregates total spending per city.

4. **Data Visualization**
   - Plots total spending per city using Seaborn bar charts.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshyambanjade/SQLite-with-Python.git
   cd SQLite-with-Python
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Run the script:
   ```bash
   python script.py
   ```

## Use Case

This project is ideal for beginners in data science or backend development looking to understand:
- Database integration with Python.
- Performing SQL operations via Pandas.
- Simple data analytics and visualization.
