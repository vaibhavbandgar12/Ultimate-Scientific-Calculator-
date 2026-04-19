# Ultimate Scientific Calculator Pro

Welcome to the **Ultimate Scientific Calculator Pro** project! This is a feature-rich, desktop-based scientific calculator built using Python and the Tkinter library. It provides a sleek, dark-themed user interface with powerful calculation capabilities.

## 🚀 Overview

The Ultimate Scientific Calculator Pro allows users to perform basic arithmetic operations as well as advanced scientific calculations. It is designed to be user-friendly, handling complex mathematical expressions safely and displaying results with high precision.

## ✨ Features

- **Standard Arithmetic**: Addition (`+`), Subtraction (`-`), Multiplication (`*`), Division (`/`), and Percentages (`%`).
- **Advanced Scientific Functions**:
  - Trigonometric limits: `sin`, `cos`, `tan`, `cosec`, `sec`, `cot` (Calculated in degrees).
  - Logarithmic operations: Base 10 logarithms (`log`).
  - Exponential & Roots: Square root (`√`), square (`x²`), cube (`x³`), `e^x`, `10^x`, and inverse (`1/x`).
  - Factorials (`!`).
- **Constants**: Pi (`π`) and Euler's number (`e`).
- **Memory Operations**: 
  - `M+`: Add to memory
  - `M-`: Subtract from memory
  - `MR`: Recall memory
  - `MC`: Clear memory
- **Robust Error Handling**: Gracefully handles division by zero, invalid inputs, overflow, and domain errors.
- **Beautiful UI**: A modern, non-resizable dark mode UI with gold-accented buttons.

## 📁 Project Structure

```text
Ultimate Scientific Calculator Project/
│
├── Scientific_Calculator.py              # Main application source code
├── scientific calculator documentation.docx # Additional project documentation
└── README.md                             # This file
```

## 🛠️ Prerequisites

To run this application, you need to have Python installed on your computer. 
- **Python 3.x** (Tkinter is included by default in standard Python installations).

## 🏃 How to Run

1. Open your terminal or command prompt.
2. Navigate to the directory containing the project:
   ```bash
   cd "Ultimate Scientific Calculator Project"
   ```
3. Run the python script:
   ```bash
   python Scientific_Calculator.py
   ```
4. The calculator window will appear, and you can start calculating!

## 💡 How it works under the hood
The application parses the mathematical expression entered by the user, creatively rewrites symbols (like replacing `^` with `**` or parsing custom inputs like trigonometric functions) and securely evaluates the result using core Python math libraries.
