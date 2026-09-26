# Survey Feedback Analyzer

A Python-based mini project developed as part of my Python Fundamentals module.

The project analyzes survey feedback stored in a dictionary of lists and demonstrates core Python programming concepts including data structures, loops, conditional statements, string operations, and user-defined functions.

## Project Overview

The Survey Feedback Analyzer allows users to:

- Work with preloaded survey feedback
- Add new feedback entries
- Clean textual feedback
- Analyze frequently used words
- Calculate the average rating
- Find the feedback with the longest comment
- Identify unique words used in the feedback
- Sort feedback entries based on rating

## Concepts Used

- Python Dictionaries
- Python Lists
- Python Sets
- `for` loops
- `while` loops
- `if`, `elif`, and `else`
- User-defined Functions
- String Methods
- `split()` and `join()`
- `replace()`
- `lower()`
- `strip()`
- `set()`
- `zip()`
- `sorted()`
- User Input

## Features

### 1. Preloaded Feedback

The program starts with 10 predefined survey feedback entries containing:

- Serial Number
- Name
- Feedback
- Rating

### 2. Add New Feedback

Users can enter additional feedback entries by providing:

- Name
- Written Feedback
- Rating from 1 to 5

Serial numbers are automatically assigned to new entries.

### 3. Text Cleaning

The feedback text is cleaned by:

- Removing punctuation
- Removing unnecessary spaces
- Removing leading and trailing spaces
- Converting text to lowercase

### 4. Word Count Analysis

The program checks how many feedback entries contain:

- `good`
- `poor`
- `excellent`

A reusable function is used for the word-count analysis.

### 5. Feedback Insights

The program calculates:

- Average rating
- Longest feedback comment
- Word count of the longest feedback
- Unique words used across all feedback

### 6. Rating-Based Sorting

Feedback entries can also be sorted from the highest rating to the lowest rating using `zip()` and `sorted()`.

## How to Run

1. Make sure Python is installed on your system.
2. Clone or download this repository.
3. Open the project folder in your Python IDE or terminal.
4. Run the Python file:

```bash
python survey_feedback_analyzer.py
