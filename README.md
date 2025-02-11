# Polygon Area Calculator

## Overview
This project is a polygon area calculator implemented in Python. It defines classes for rectangles and squares, allowing users to compute area, perimeter, diagonal length, and visualize the shape using text-based representations. This project was a **mandatory** part of the *Scientific Computing with Python* certification on FreeCodeCamp, where I learned about object-oriented programming and class inheritance in Python.

## Features
- **Rectangle Class**: Supports width and height attributes.
- **Square Class**: Inherits from `Rectangle` but ensures both sides are equal.
- **Compute Area**: Calculates the area of the shape.
- **Compute Perimeter**: Determines the perimeter of the shape.
- **Get Diagonal**: Computes the diagonal length using the Pythagorean theorem.
- **Generate ASCII Art**: Displays the shape using `*` characters.
- **Get Amount Inside**: Determines how many times another shape can fit inside.

## Usage
1. Create a `Rectangle` object:
   ```python
   rect = Rectangle(10, 5)
   print(rect.get_area())  # Output: 50
   ```
2. Modify dimensions:
   ```python
   rect.set_height(3)
   print(rect.get_perimeter())  # Output: 26
   ```
3. Create a `Square` object:
   ```python
   sq = Square(9)
   print(sq.get_area())  # Output: 81
   ```
4. Visualize the shape:
   ```python
   print(rect.get_picture())
   ```
5. Check how many times one shape fits into another:
   ```python
   rect.set_height(8)
   rect.set_width(16)
   print(rect.get_amount_inside(sq))
   ```

## Dependencies
- Python 3.x (No external libraries required)

## Acknowledgments
This project was a **mandatory** part of the *Scientific Computing with Python* certification on FreeCodeCamp, where I enhanced my understanding of object-oriented programming and class inheritance in Python.

