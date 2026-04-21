# Calculator

A simple and elegant calculator application built with Python's Tkinter library.

## Features

- **Basic Operations**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Advanced Functions**: Square (x²) and Square Root (√x)
- **Keyboard Support**: Full keyboard input for all operations
- **Clean Interface**: Modern design with intuitive layout
- **Error Handling**: Graceful handling of invalid expressions

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## Installation

1. Clone or download this repository
2. Navigate to the Calculator directory
3. Run the application:

```bash
python Calculator.py
```

## Usage

### Mouse Interface
- Click on number buttons (0-9) to input digits
- Click on operator buttons (+, -, ×, ÷) to perform operations
- Click on special functions:
  - `C`: Clear all entries
  - `x²`: Square the current number
  - `√x`: Calculate square root of the current number
  - `=`: Evaluate the expression

### Keyboard Interface
- **Numbers**: Press 0-9 keys
- **Operators**: Press +, -, *, / keys
- **Equals**: Press Enter key
- **Decimal**: Press . (period) key

## Interface Layout

```
┌─────────────────────┐
│   Total Expression  │
│ Current Expression  │
├─────┬─────┬─────┬─────┐
│  C  │ x²  │ √x  │  ÷  │
├─────┼─────┼─────┼─────┤
│  7  │  8  │  9  │  ×  │
├─────┼─────┼─────┼─────┤
│  4  │  5  │  6  │  -  │
├─────┼─────┼─────┼─────┤
│  1  │  2  │  3  │  +  │
├─────┼─────┼─────┼─────┤
│  .  │  0  │      │  =  │
└─────┴─────┴─────┴─────┘
```

## Technical Details

- **Framework**: Tkinter
- **Window Size**: 350x650 pixels (resizable)
- **Color Scheme**: Pink (#D7005F) on light backgrounds
- **Font Styles**: Arial family with varying sizes for different UI elements

## Error Handling

The calculator gracefully handles:
- Division by zero
- Invalid mathematical expressions
- Square root of negative numbers

In case of errors, "Error" will be displayed in the current expression area.

## File Structure

```
Calculator/
├── Calculator.py    # Main application file
└── README.md       # This documentation file
```

## License

This project is open source and available under the MIT License.
