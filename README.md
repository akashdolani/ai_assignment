# ai_assignment
# Salary vs CGPA Plot

This project visualizes the relationship between salary and CGPA using a simple line plot created with Matplotlib.

## Description
The plot demonstrates how CGPA values correspond to salaries, showcasing a trend. It uses Python's Matplotlib library for visualization.

## Code
Below is the Python code used to generate the plot:

```python
import matplotlib.pyplot as plt

salary = [40000, 42500, 45000, 47500]
cgpa = [7, 8, 8.5, 9]

plt.plot(salary, cgpa)
plt.title("Salary vs CGPA")
plt.xlabel("Salary")
plt.ylabel("CGPA")
plt.show()
