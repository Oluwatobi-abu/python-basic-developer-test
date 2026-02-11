🧠 Python Basic Developer Test – Bincom ICT
📌 Project Overview

This project analyzes the colours of dresses worn by Bincom ICT staff during the week and performs statistical analysis to help determine suitable T-shirt production colours.

The program extracts colour data from an HTML file, cleans inconsistencies, performs statistical computations, stores results in PostgreSQL, and implements additional algorithmic tasks.

🚀 Features Implemented

1️⃣ Data Extraction

Extracts colour data from an HTML table using Regular Expressions.

2️⃣ Data Cleaning

Corrects spelling errors such as:

BLEW → BLUE

ARSH → ASH

3️⃣ Statistical Analysis

Frequency of each colour

Mean colour (via numeric mapping)

Median colour

Most worn colour (Mode)

Variance

Probability of selecting RED

Note: Since colours are categorical data, mean and variance are computed after numeric mapping for academic purposes.

4️⃣ Database Integration

Saves colour frequencies into PostgreSQL database.

5️⃣ Algorithms Implemented

Recursive search algorithm

Random 4-bit binary number generation and base-10 conversion

Sum of first 50 Fibonacci numbers

🛠 Technologies Used

Python 3

Regular Expressions (re)

Collections (Counter)

PostgreSQL

psycopg2

Basic Algorithms & Recursion

📂 Project Structure
Python Basic Developer Test/
│
├── Python Basic Developer Test.py
├── python_class_question.html
└── README.md

⚙️ Installation & Setup
1️⃣ Install Python

Download from:
https://www.python.org

2️⃣ Install Required Package
pip install psycopg2-binary

3️⃣ Configure Database

Update this section in the code:

database="bincom_test",
user="postgres",
password="your_password"


Then uncomment:

save_to_postgres(frequency)

▶️ How to Run

Open PowerShell in project folder:

python "Python Basic Developer Test.py"

📊 Sample Output

Most Worn Colour: BLUE

Probability of RED: 0.0947

Sum of first 50 Fibonacci numbers: 20365011073

🧑‍💻 Author

Abubakar Oluwatobi
Python Developer

