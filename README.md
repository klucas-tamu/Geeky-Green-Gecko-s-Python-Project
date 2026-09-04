# Geeky-Green-Gecko-s-Python-Project
Python Project for ISTM 601
The Geeky Green Geckos' Personal Finance Tracker is a modular Python application developed for ITSM 601. The application allows users to record income and expenses, categorize transactions, generate financial reports, and display spending patterns through visualizations created with Turtle Graphics.

Project Goals

The primary goal of this project is to create a simple, modular personal finance application while demonstrating Python programming concepts, file handling, data validation, financial calculations, reporting, testing, and data visualization.

Features
Record income and expenses
Validate transaction data
Categorize transactions
Save and load transaction data using CSV files
Generate financial summaries and reports
Generate period-based and monthly reports
Generate category-based reports
Create expense visualizations using Turtle Graphics
Automated testing of core functionality
Modular architecture separating input, processing, storage, reporting, and visualization
Project Structure
Geeky-Green-Gecko-s-Python-Project/
│
├── data/
│   └── transactions.csv
│
├── docs/
│   ├── Phase-1-Project-Proposal.pdf
│   ├── Phase-2-Project-Report.pdf
│   ├── Phase-3-Project-Report.pdf
│   ├── Phase-4-Project-Report.pdf
│   └── architecture_diagram.png
│
├── images/
│   └── bar-chart.png
│
├── src/
│   ├── main.py
│   ├── models.py
│   ├── storage.py
│   ├── finance.py
│   ├── reports.py
│   └── visualization.py
│
├── tests/
│   └── [automated test files]
│
└── README.md
Module Responsibilities
Module	Responsibility
src/main.py	Command-line interface and main() entry point. Controls the primary user interaction and coordinates the other modules.
src/models.py	Defines and validates the transaction data model used throughout the application.
src/storage.py	Handles loading and saving transaction data using CSV files.
src/finance.py	Handles input validation and financial calculations used by the application.
src/reports.py	Generates period-based, category-based, and monthly financial reports.
src/visualization.py	Generates expense visualizations using Turtle Graphics.
tests/	Contains automated tests used to verify the application's core functionality.
Setup

Python 3.10 or newer is required. A virtual environment is recommended:

python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -e ".[dev]"

No runtime libraries outside the Python standard library are required.

Run

Start the application with:

python3 -m src.main

Transactions are saved to:

data/transactions.csv

Enter dates using the YYYY-MM-DD format, positive amounts as currency values, and transaction types as either income or expense.

The chart option requires a desktop environment that supports Tk.

Testing

Automated tests can be run using:

python3 -m pytest

The application separates input, processing, storage, reporting, and output so team members can work on individual modules without changing the command-line interface.

Architecture

The application follows a modular architecture that separates the major responsibilities of the program.




This structure allows individual components to be developed, tested, and modified independently while maintaining a consistent user interface.

Project Documentation

The development of the Personal Finance Tracker was completed through multiple project phases.

Phase 1 – Project Proposal
Phase 2 – Project Report
Phase 3 – Project Report
Phase 4 – Project Report
Example Visualization

The application uses Turtle Graphics to visualize expenses by category and help users better understand their spending patterns.




Development Approach

The project uses a modular design so that different team members can work on specific components without unnecessarily affecting other parts of the application.

The primary separation of responsibilities includes:

Input → Processing → Storage → Reporting → Visualization

This approach improves organization, testing, maintainability, and collaboration throughout the project.

Generative AI Disclosure

Generative AI may be used as a collaborative coding assistant for brainstorming, implementation, debugging, and documentation. The team is responsible for reviewing, explaining, testing, and adapting all generated code before submission.
