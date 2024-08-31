## Person Details 

Name: Harshada Ganesh Tupe

Company: CODTECH IT SOLUTIONS PVT.LTD

Task Name: Student Grades Tracker (CODTECH TASK 1)

Domain: Python Programming

Duration: 1 August to 1 September 2024

Mentor: Muzammil Ahmed

Intern ID: CT08DS6116


## Overview Of The Project 

## Description
The Student Grades Tracker is a Python program designed to help users manage and track student grades. The program allows users to input grades for different subjects or assignments, calculate average grades, and display overall grades along with additional information such as letter grades and GPA.

## Features
- Input grades for multiple subjects or assignments.
- Calculate and display the average grade.
- Show letter grades based on the average grade.
- Calculate and display the GPA (Grade Point Average).

## Installation

To use this program, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/t-harshada01/Grade_Calculator.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd student-grades-tracker
   ```
3. **Ensure you have Python installed.** The program is compatible with Python 3.6 and above. You can download Python from [python.org](https://www.python.org/).

## Usage

1. **Run the Program:**
   ```bash
   python grades_tracker.py
   ```
2. **Input Grades:**
   The program will prompt you to enter grades for various subjects or assignments. Enter each grade followed by pressing Enter.

3. **View Results:**
   After inputting all grades, the program will display:
   - The average grade.
   - The letter grade corresponding to the average grade.
   - The GPA based on the average grade.

## Example

```text
Enter the grades for the subjects (type 'done' when finished):
Math: 85
Science: 90
History: 78
English: 88
done

Average Grade: 85.25
Letter Grade: B
GPA: 3.2
```

## Code Example

Here's a snippet of the code that calculates the average grade and letter grade:

```python
def calculate_average(grades):
    return sum(grades) / len(grades)

def get_letter_grade(average):
    if average >= 90:
        return 'A'
    elif average >= 80:
        return 'B'
    elif average >= 70:
        return 'C'
    elif average >= 60:
        return 'D'
    else:
        return 'F'

def calculate_gpa(average):
    if average >= 90:
        return 4.0
    elif average >= 80:
        return 3.0
    elif average >= 70:
        return 2.0
    elif average >= 60:
        return 1.0
    else:
        return 0.0
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

