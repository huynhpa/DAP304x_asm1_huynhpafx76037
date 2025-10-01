# DAP304x Assignment 1: Exam Grading Program

## Overview
This project is developed for the DAP304x course to create a Python program that grades exams based on input data files. The program processes student answers, validates data, calculates scores, generates statistical reports, and outputs results to a file.

## Features
- **Task 1**: Prompts the user to input a class file name (e.g., `class1` for `class1.txt`) and checks its existence using `try/except`.
- **Task 2**: Validates data lines, reporting errors for invalid lines (incorrect number of values or invalid student IDs).
- **Task 3**: Grades exams using a predefined answer key, calculates statistics (high scores, mean, highest/lowest scores, range, median), and identifies questions most skipped or answered incorrectly.
- **Task 4**: Saves student IDs and scores to an output file (e.g., `class1_grades.txt`).
- **Task 5**: Utilizes only `pandas` and `numpy` for data processing and file output.

## File Structure
- `lastname_firstname_grade_the_exams.py`: The main Python script implementing the grading logic.
- Input files (e.g., `class1.txt`, `class2.txt`): Sample data files containing student answers (not included in submission).
- Output files (e.g., `class1_grades.txt`): Generated files containing student IDs and scores.

## Requirements
- Python 3.9
- Libraries: `pandas`, `numpy`

## Installation
1. Install Python 3.9.
2. Install required libraries:
   ```bash
   pip install pandas numpy
   How to RunPlace input data files (e.g., class1.txt) in the same directory as the script.
Run the program:bash

python lastname_firstname_grade_the_exams.py

Enter the class file name (e.g., class1) when prompted.
The program will:Validate the input file and data.
Grade exams and display statistical reports.
Generate an output file (e.g., class1_grades.txt) with student IDs and scores.

Submission DetailsFolder Name: DAP304x_asm1_<YourAccount> (e.g., DAP304x_01_huynhpaFX76037@funix.edu.vn)
Files Included:lastname_firstname_grade_the_exams.py
README.md

Format: The folder is zipped into a .zip file for submission.
Note: Input and output data files are not included in the submission unless specified.

NotesThe program handles invalid data with detailed error messages.
Floating-point values (e.g., mean, median, percentages) are rounded to 3 decimal places.
The output file format contains student IDs and scores, separated by commas, without headers.

# DAP304x Assignment 1: Exam Grading Program

## Overview
This project is developed for the DAP304x course to create a Python program that grades exams based on input data files. The program reads student answers from text files, validates the data, calculates scores, generates statistical reports, and saves results to an output file.

## Features
- **Task 1**: Prompts the user to input a class file name (e.g., `class1` for `class1.txt`) and validates its existence using `try/except`.
- **Task 2**: Analyzes data lines, reporting errors for invalid lines (incorrect number of values or invalid student IDs).
- **Task 3**: Grades exams using a predefined answer key, calculates statistics (high scores, mean, highest/lowest scores, range, median), and identifies questions most skipped or answered incorrectly.
- **Task 4**: Saves student IDs and scores to an output file (e.g., `class1_grades.txt`).
- **Task 5**: Uses only `pandas` and `numpy` libraries for data processing and file output.

## File Structure
- `lastname_firstname_grade_the_exams.py`: The main Python script implementing the grading logic.
- Input files (e.g., `class1.txt`, `class2.txt`): Sample data files containing student answers (not included in submission).
- Output files (e.g., `class1_grades.txt`): Generated files containing student IDs and scores.

## Requirements
- **Python Version**: Python 3.9
- **Libraries**: `pandas`, `numpy`

## Installation
Follow these steps to set up the environment:
1. **Install Python 3.9**:
   - Download and install Python 3.9 from [python.org](https://www.python.org/downloads/release/python-390/).
   - Verify the installation by running:
     ```bash
     python --version
     ```
     Ensure the output shows `Python 3.9.x`.
2. **Install required libraries**:
   - Open a terminal or command prompt and run:
     ```bash
     pip install pandas numpy
     ```
   - Verify installation:
     ```bash
     pip show pandas
     pip show numpy
     ```

## How to Run
Follow these steps to execute the program:
1. **Prepare input files**:
   - Place the input data files (e.g., `class1.txt`, `class2.txt`) in the same directory as the script.
   - Each input file should contain student data in the format:
     ```
     N12345678,B,A,D,D,C,B,D,A,C,C,D,B,A,B,A,C,B,D,A,C,A,A,B,D,D
     ```
     where the first value is a student ID (starting with 'N' followed by 8 digits), followed by 25 comma-separated answers (A, B, C, D, or empty for skipped questions).
2. **Run the program**:
   - Open a terminal or command prompt.
   - Navigate to the directory containing the script:
     ```bash
     cd /path/to/your/project/folder
     ```
   - Execute the script:
     ```bash
     python lastname_firstname_grade_the_exams.py
     ```
3. **Interact with the program**:
   - When prompted, enter the class file name (e.g., `class1` for `class1.txt`).
   - Example prompt:
     ```
     Enter a class file to grade (i.e. class1 for class1.txt): class1
     ```
   - If the file is not found, the program will display:
     ```
     File cannot be found.
     ```
     and prompt for another file name.
4. **Program output**:
   - If the file is valid, the program will:
     - Display a confirmation: `Successfully opened class1.txt`.
     - Analyze the data and report invalid lines (if any).
     - Calculate and display statistics:
       - Total valid and invalid lines.
       - Number of students with scores > 80.
       - Mean, highest, lowest, range, and median scores.
       - Questions most skipped and answered incorrectly (with counts and percentages).
     - Generate an output file (e.g., `class1_grades.txt`) containing student IDs and scores in the format:
       ```
       N00000001,59
       N00000002,70
       ...
       ```
5. **Example output** for `class1_grades.txt`:



