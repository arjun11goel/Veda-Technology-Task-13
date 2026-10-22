# Task 13: NumPy Data Filtering

## Description
This project demonstrates how to use NumPy conditions to identify values that are above, below, or equal to a specified threshold. The primary objective is to practice Boolean indexing and numerical filtering on datasets.

## Objective
Practice Boolean indexing and numerical filtering using Python and NumPy.

## Tools Used
* Python
* NumPy
* Jupyter Notebook

## Suggested Datasets
* Student marks (used in this implementation)
* Sales values

## Execution Results

Based on the simulated student marks dataset, here are the filtering results:

* **Original Array (Student Marks):** `[45 78 92 33 85 60 55 98 41 70]`
* **Marks > 75:** `[78 92 85 98]`
* **Marks < 50:** `[45 33 41]`
* **Marks equal to 60:** `[60]`
* **Marks between 60 and 80:** `[78 60 70]`

## Interview Questions & Answers

**1. What is Boolean indexing?**
Boolean indexing is a technique in NumPy (and Pandas) where you use an array of Boolean values (True/False) to select elements from another array. The resulting array contains only the elements corresponding to the `True` values in the Boolean mask.

**2. How do you filter a NumPy array?**
You filter a NumPy array by creating a condition that evaluates to a Boolean mask (e.g., `array > 10`), and then passing that mask inside square brackets to index the original array (e.g., `filtered_array = array[array > 10]`).

**3. What is a Boolean array?**
A Boolean array is a NumPy array where every element is either `True` or `False`. They are often the result of applying logical operators (like `>`, `<`, `==`) to a numerical array.
