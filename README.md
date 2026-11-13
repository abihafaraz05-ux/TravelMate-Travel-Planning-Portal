# TravelMate – Travel Planning and Management Portal

## Project Overview

TravelMate is a Python-based travel planning portal developed as part of Assignment No. 3 – End-to-End Portal Design.

The system allows users to register, log in, create travel plans, search destinations, view saved trips and generate travel summary reports.

It uses Python for backend development, JSON for data storage and Streamlit for the frontend.

## Features

- User registration and login
- Add new travel plans
- View previously saved travel plans
- Search destinations
- Generate travel summary reports
- Calculate total and average estimated travel budgets
- Persistent data storage using JSON files
- Interactive Streamlit interface

## Technologies Used

- Python
- Streamlit
- JSON
- Jupyter Notebook
- GitHub

## Project Files

| File | Description |
|---|---|
| travel_backend.py | Backend functions and console menu |
| streamlit_app.py | Streamlit frontend |
| users.json | User account data |
| travel_plans.json | Travel plan records |
| TravelMate_Notebook.ipynb | Code explanations and test runs |
| requirements.txt | Required Python packages 

## Installation and Execution

### Step 1: Install Python

Make sure Python is installed on your computer.

### Step 2: Install dependencies

Run the following command:

```bash
pip install -r requirements.txt
```

### Step 3: Run the console version

```bash
python travel_backend.py
```

### Step 4: Run the frontend

```bash
streamlit run streamlit_app.py
```

The application will open in your web browser.

## Data Storage

The portal uses JSON files to store user accounts and travel plans. Existing records are loaded when the application starts, and updated records are saved automatically.

## Project Purpose

This project demonstrates modular programming, loops, conditional statements, exception handling, file handling and persistent data storage using Python.

## Developers

- Member 1: Abiha Faraz (25L-5199)
- Member 2: Noor Fatima (25L-5164)

FAST School of Management  
National University of Computer and Emerging Sciences
