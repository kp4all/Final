
# Matrix Calculator

**Author**: Kapil  
**Credits**: ChatGPT, Acode App, Mimo

## Overview

The Matrix Calculator is a simple web-based tool that allows users to perform basic matrix operations like addition, subtraction, multiplication, and division between rows of a 3x4 matrix. Users can input values into the matrix, select which rows to operate on, and choose an operation to apply. The result is displayed dynamically on the page.

## Features

- **Matrix Input**: Allows the user to input values for a 3x4 matrix.
- **Row Selection**: Users can select two rows from the matrix (R1, R2, or R3) from the dropdown menus.
- **Operations Supported**: 
  - Addition
  - Subtraction
  - Multiplication
  - Division
- **Scaling Factors**: Input scaling factors for both rows to apply during the operation.
- **Responsive Design**: Grid layout for easy matrix input and intuitive row selection and operation handling.

## How to Use

1. **Input Matrix Values**: Fill in the matrix with the values you'd like to work with.
2. **Select Rows**: Choose two rows from the matrix (R1, R2, or R3) from the dropdown menus.
3. **Choose an Operation**: Select one of the operations (Add, Subtract, Multiply, Divide).
4. **Scaling Factors**: Input the scaling factor for each row if you want to scale the values before performing the operation.
5. **Solve**: Press the "SOLVE" button to see the result.

### Example

1. Input matrix values:
   ```
   1  2  3  4
   5  6  7  8
   9 10 11 12
   ```

2. Select row 1 and row 2.

3. Select **Add** as the operation.

4. Enter scaling factors (e.g., 1 for row 1 and 1 for row 2).

5. Click **SOLVE**. The result of adding the first and second rows will be displayed.

## File Structure

- **index.html**: The main HTML file that sets up the structure and layout of the page.
- **CalcM.css**: The CSS file for styling the calculator and giving it a modern, responsive layout.
- **CalcM.js**: The JavaScript file that handles all the operations and interactions between the user input and the matrix calculations.

## Credits

- **Kapil**: Creator of this matrix calculator project.
- **ChatGPT**: Assistance with the logic and coding of the project.
- **Acode App**: Used for writing and testing the code.
- **Mimo**: Learning platform that contributed to development knowledge.

## Future Improvements

- **Error Handling**: Add checks for invalid inputs like division by zero.
- **More Operations**: Implement more complex matrix operations such as matrix inversion, determinants, etc.
- **Larger Matrices**: Allow the user to define custom matrix sizes.

## Installation

No installation is required! Simply open the `index.html` file in your browser, and the calculator is ready to use.
