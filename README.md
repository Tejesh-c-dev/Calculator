# Modern Calculator

A sleek, responsive calculator web application built with HTML, CSS, and JavaScript. This calculator provides a user-friendly interface with both mouse and keyboard support for performing basic mathematical operations.

![Calculator Preview](preview.png)

## Features

### Basic Operations
- Addition (+)
- Subtraction (-)
- Multiplication (×)
- Division (/)
- Percentage (%)
- Decimal numbers support

### User Interface
- Clean, modern design with a responsive layout
- Color-coded buttons for better user experience
  - Blue: Operators (+, -, ×, ÷)
  - Red: Special functions (AC, DEL)
  - Green: Equals button (=)
  - Gray: Numbers and decimal point
- Smooth animations and hover effects
- Expression history display
- Error handling for invalid expressions

### Smart Features
- Expression history tracking
- Automatic decimal point handling
- Proper percentage calculations
- Number formatting for cleaner results
- Prevention of invalid operations

### Keyboard Support
The calculator can be operated using your keyboard:
- Numbers (0-9) for digit input
- Operators (+, -, *, /)
- Enter or = for calculation
- Backspace for delete
- Escape for clear all
- Decimal point (.)
- Percentage symbol (%)

## Technical Details

### File Structure
```
Calculator/
│
├── index.html      # Main HTML file
├── style.css       # CSS styling
└── README.md       # Documentation
```

### Technologies Used
- HTML5
- CSS3 (with Grid and Flexbox)
- Vanilla JavaScript
- Responsive Design
- CSS Transitions for animations

### Key Components
1. **Display System**
   - Main display for current input
   - History display for previous calculations

2. **Button Grid**
   - 4x5 grid layout
   - Special sizing for zero button (spans 2 columns)

3. **JavaScript Functions**
   - `appendValue()`: Handles number and operator input
   - `clearDisplay()`: Resets the calculator
   - `deleteLast()`: Removes the last entered character
   - `calculate()`: Processes and evaluates the expression

## Responsive Design
The calculator is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- Different screen sizes and orientations

## Browser Compatibility
Works on all modern browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

## Usage Instructions

1. Opening the Calculator:
   - Open `index.html` in any modern web browser

2. Performing Calculations:
   - Click buttons or use keyboard for input
   - Use AC to clear all
   - Use DEL to remove last entry
   - Press = or Enter to calculate

3. Using Percentages:
   - Enter a number
   - Press % to convert to percentage
   - Continue with other operations if needed

## Development

### To Modify:
1. Edit `index.html` for structure changes
2. Modify `style.css` for styling updates
3. Update JavaScript code in `index.html` for functionality changes

### Best Practices Used:
- Semantic HTML5 elements
- CSS Grid for layout
- Event delegation for buttons
- Error handling for calculations
- Input validation
- Responsive design principles

## Future Enhancements
Possible improvements that could be added:
- Scientific calculator functions
- History log of calculations
- Memory functions (M+, M-, MR, MC)
- Theme switcher (Light/Dark mode)
- Keyboard shortcuts customization

## License
This project is open source and available under the MIT License.

## Author
[Your Name]
- Student ID: 1SI24CS189
- Course: Computer Science Engineering
- Institution: [Your Institution Name]

---

Feel free to contribute to this project by submitting issues or pull requests!
