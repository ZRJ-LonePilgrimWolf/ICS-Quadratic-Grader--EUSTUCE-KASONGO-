# Quadratic Equation Solver & Grade Calculator

A single-file web application that solves quadratic equations and converts numerical scores to letter grades.

## Features

- **Quadratic Equation Solver**: Calculates roots for equations of the form ax² + bx + c = 0
  - Handles real and complex roots
  - Shows discriminant and nature of roots
  - Input validation with friendly error messages

- **Grade Calculator**: Converts numerical scores (0-100) to letter grades
  - Uses the standard grading scale (A+, A, B+, B, C+, C, D)
  - Input validation for score range

## How to Run

1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. The application runs completely offline - no internet connection required

Alternatively, you can simply double-click the `index.html` file to open it in your default browser.

## Test Cases

### Quadratic Equation Solver
- a=1, b=-3, c=2 → Roots: 2 and 1 (two distinct real roots)
- a=1, b=-2, c=1 → Root: 1 (one repeated real root)
- a=1, b=2, c=5 → Roots: -1 ± 2i (complex conjugate roots)

### Grade Calculator
- 95 → A+
- 82 → A
- 70 → B+
- 62 → B
- 57 → C+
- 52 → C
- 45 → D
- 0 → D
- 100 → A+

## Technologies Used

- HTML5
- CSS3 (with responsive design)
- JavaScript (vanilla, no frameworks)

## Repository Structure
