# Student Performance Analysis System

## Project Overview

The **Student Performance Analysis System** is a Python-based command-line application designed to manage student records and analyze academic performance.

The system allows users to add, view, search, update, and delete student records. It also calculates performance statistics such as averages, highest and lowest performers, pass/fail counts, and subject-wise performance.

The project demonstrates modular Python programming, data management, validation, algorithms, analysis, reporting, and basic automated testing.

## Features

* Add student records
* View all students
* Search for a student
* Update student information
* Delete student records
* Validate student information and marks
* Analyze class performance
* Calculate student averages and totals
* Identify highest and lowest performers
* Calculate pass/fail counts
* Perform subject-wise analysis
* Generate individual student reports
* Generate class reports
* Generate subject reports
* Load fixed sample data
* Run automated program verification

## Technologies Used

* Python 3
* Lists
* Dictionaries
* Sets
* Functions
* Modules
* Conditional statements
* Loops
* Fundamental algorithms

## Project Structure

```text
StudentPerformanceSystem/
│
├── main.py
├── algorithms.py
├── analysis.py
├── data_manager.py
├── reports.py
├── sample_data.py
├── test_cases.py
├── validation.py
├── statement.md
└── README.md
```

### File Description

| File              | Purpose                                                                              |
| ----------------- | ------------------------------------------------------------------------------------ |
| `main.py`         | Main command-line interface and program execution                                    |
| `algorithms.py`   | Implements performance-related algorithms and calculations                           |
| `analysis.py`     | Performs student, class, and subject-wise analysis                                   |
| `data_manager.py` | Handles student record management operations                                         |
| `reports.py`      | Generates individual, class, and subject reports                                     |
| `sample_data.py`  | Provides fixed sample student data                                                   |
| `test_cases.py`   | Contains automated tests for important program operations                            |
| `validation.py`   | Validates student information and marks                                              |
| `statement.md`    | Contains the project problem statement, scope, target users, and high-level features |
| `README.md`       | Project documentation and setup instructions                                         |

## Requirements

The project requires:

* Python 3.8 or higher
* A terminal or command prompt
* Git (only required if cloning the project from GitHub)

No external Python libraries are required.

## Installation and Setup

### 1. Clone the Repository

Clone the repository using Git:

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

Move into the project directory:

```bash
cd StudentPerformanceSystem
```

Replace `<YOUR-GITHUB-REPOSITORY-URL>` with the URL of this project's GitHub repository.

### 2. Verify Python Installation

Check that Python is installed:

```bash
python --version
```

If the `python` command is not available on your system, try:

```bash
py --version
```

Python 3.8 or higher is recommended.

### 3. Install Dependencies

This project does not require any external Python packages.

No `pip install` command is necessary.

## Running the Project

From the project directory, run:

```bash
python main.py
```

On Windows, if `python` is not recognized, use:

```bash
py main.py
```

The program will start in the terminal and display the available operations.

Follow the on-screen prompts to manage student records, perform analysis, and generate reports.

## Running the Tests

The project includes automated verification in `test_cases.py`.

Run the tests using:

```bash
python test_cases.py
```

On Windows, you can also use:

```bash
py test_cases.py
```

The test program checks important functionality of the system, including data operations, validation, calculations, and analysis.

## Sample Data

The project includes predefined sample student data in:

```text
sample_data.py
```

This allows the system to be tested with fixed records without manually entering every student record.

## Usage

After starting the program:

```bash
python main.py
```

use the options displayed in the terminal to perform operations such as:

1. Adding a student
2. Viewing student records
3. Searching for a student
4. Updating student information
5. Deleting a student
6. Analyzing performance
7. Generating reports
8. Loading sample data
9. Running available verification operations
10. Exiting the program

The exact menu options displayed by the program should be followed during execution.

## Input Validation

The system validates user input before processing it.

Examples include:

* Checking required student information
* Validating marks
* Preventing invalid mark ranges
* Handling invalid menu choices
* Preventing invalid student records from being processed

## Project Limitations

The current version is a command-line application and does not include:

* A graphical user interface
* A web interface
* User authentication
* An external database
* Cloud storage
* Online synchronization

Student data is handled during program execution using Python data structures.

## Future Enhancements

Possible future improvements include:

* Adding a graphical user interface
* Adding database storage
* Adding user authentication
* Exporting reports to CSV or PDF
* Adding graphical performance charts
* Supporting multiple classes
* Adding persistent data storage

## Author

Student Performance Analysis System developed as part of the flipped course project evaluation.
