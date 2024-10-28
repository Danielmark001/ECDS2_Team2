# MACS1_Team2

This project processes student group assignment data focusing on balanced gender ratio, minimal GPA variation, and diverse school representation. and visualizes group compositions based on gender, GPA, and school distribution.

## Overview

The code reads data from a CSV file, `records.csv`, and creates visualizations to help the course coordinator understand the composition of each group. The visualizations include:
- **Gender Distribution** by group
- **Average GPA** per group
- **School Distribution** within each group

## Prerequisites

- Python 3.6 or later
- Matplotlib

## Installation

1. Clone the repository or download the project files.
2. Ensure you have `pip` installed.
3. Install the required libraries by running:

    ```bash
    pip install -r requirements.txt
    ```

## Data Format

The `records.csv` file should have the following columns:
- **Tutorial Group**: Group identifier (e.g., G-1)
- **Student ID**: Unique identifier for each student
- **School**: School or department of each student (e.g., EEE, MAE)
- **Name**: Name of the student
- **Gender**: Gender of the student (Male/Female)
- **GPA**: GPA score of the student


## Example Output CSV File

| Tutorial Group | Student ID | School   | Name           | Gender | GPA | Team Assigned |
|----------------|------------|----------|----------------|--------|-----|---------------|
| G-1            | 5002       | CCDS     | Aarav Singh    | Male   | 4.02| 1             |
| G-1            | 3838       | EEE      | Aarti Nair     | Female | 4.05| 1             |
| G-1            | 2091       | EEE      | Adlan Bin Rahman| Male   | 4.20| 2             |

