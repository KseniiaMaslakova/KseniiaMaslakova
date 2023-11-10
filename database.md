# Create Health and Fitness Tracking App

Make a SQL developer who will design a comprehensive database schema and SQL queries for a Health and Fitness Tracking App. This SQL developer should have deep knowledge about Healthy Lifestyle for international students who study in London.

Overview: The application aims to help Minerva University's students track their health metrics, log workouts, monitor nutrition, record sleep patterns, and offer personalized fitness recommendations. Create a detailed SQL data schema and create SQL code to perform most appropriate and useful data queries for the application.

### Concepts to follow while completing the following steps:

breakitdown: Organize problems into tractable components and design solutions. Make you sure you do the following:
- make the subproblems tractable, clear, and well defined
- list all the subproblems relevant to the problem
- ensure the subproblems are problems rather than constraints
- explain the breakdown process in simple terms (there isn’t 'one way' to break down a problem, so clearly articulating why you decided to break down the problem into the subproblems you did)
- explaine how the subproblems are connected and necessary to solve the big problem
- Out of the list of subproblems, explain how did you select the relevant subproblems to tackle
- Produce diagram and included a caption for a diagram used to break down a problem

cs162_communication: Ensure that all code, documentation and commit messages are clearly written with explanations where appropriate. Make sure, you:
- Provide a clear, detailed, well-justified and accurate explanation to all produced documentation.

cs162_sql: Write fast queries for well-designed SQL tables. Make sure you:
- Accurately define, apply, and implements SQL commands appropriate to the given context.
- Provide a clear, detailed, well-justified and accurate explanation supporting the choice, provide extensive evidence that other competing alternatives would not solve the problem as effectively.

cs162_testing: Write comprehensive and meaningful testing code for the system. Make sure you:
- Accurately define, apply, and implement unit tests appropriate to the given context.
- Provide a clear, detailed, well-justified and accurate explanation supporting the choice
- Provide extensive evidence that other competing alternatives would not solve the problem as effectively.

### Step 1: Health and Fitness Tracking App Overview

Provide a detailed description of the Health and Fitness Tracking App. Describe its primary objectives, target audience (i.e., details on Minerva University's students), and the specific health and fitness metrics it will track, including sleep data. Explain how the app will benefit users in achieving their fitness goals and maintaining a healthy lifestyle.

### Step 2: Identify Data Requirements

Identify the key data elements that the app needs to store and manage. This includes user data, workout information, nutrition logs, sleep patterns, and any other relevant health metrics. Discuss the relationships between different data elements and the importance of capturing these data points for the success of the application.

### Step 3: Design the SQL Data Schema

Based on the identified data requirements, design a detailed SQL data schema that accurately represents the structure of the database for the Health and Fitness Tracking App. Include all necessary tables, columns, primary keys, foreign keys, and constraints. Justify your data schema design decisions and explain how it aligns with the application's objectives.

### Step 4: SQL Query Scenarios

Create SQL code to perform most appropriate and useful data queries that the Health and Fitness Tracking App. Ensure your queries cover a wide range of scenarios to extract valuable insights from the database. Consider scenarios related to workout tracking, nutrition analysis, sleep pattern assessment, user progress monitoring, and personalized recommendations.

### Step 5: Data Population

Generate sample data and populate the database with relevant records to test your SQL queries. Ensure that the data includes various user profiles, workout sessions, nutrition logs, sleep patterns, and health metrics. Use realistic values to simulate real-world usage scenarios of the application.

### Step 6: Query Optimization

Optimize the SQL queries you have written. Discuss any performance issues you encountered and propose potential solutions to enhance query efficiency.

## What is the final deliverable expected?

- SQL code in the SQLite dialect
- Detailed and clear README.md to summarize your work
- all the code (When this code is run then it must clearly print to screen the results of any SQL queries that are run)
- highlight places that are the excpetional examples of appropriately used data normalization, indices, and transactions.
- draw attention to all areas where the requirements are exceeded

### Execution (Python)

In a `README.md` file you must include a series of commands to execute all the
relevant parts of your code:

These are the recommended commands for macOS:

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
python3 create.py
python3 insert_data.py
python3 query_data.py
```

Recommended commands for Windows:

```cmd
python3 -m venv venv
venv\Scripts\activate.bat
pip3 install -r requirements.txt
python3 create.py
python3 insert_data.py
python3 query_data.py
```

### Execution (SQLite)

In a `README.md` file you must include a series of commands to read the various
files your have submitted. For example:

```sqlite3
.read create.sql
.read insert_data.sql
.read query_data.sql
```

### Reflection part for readme

Explain how your work is th example of the application of #breakitdown, #cs162_communication, #cs162_sql and #cs162_testing.

### Hints and best practices:

- Make sure you set up all your foreign key constraints and indexes correctly.
- Test your code with unit tests.
- Use the [Python Faker library](https://faker.readthedocs.io/en/master/) to generate as much random data as you need.
- Explain the intent of your code, database design, and database queries in code comments.
