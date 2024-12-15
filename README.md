# Simple-Calculator Application

This repository contains a simple calculator web application built using HTML, CSS, and JavaScript. The calculator allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- **Arithmetic Operations**: Addition, subtraction, multiplication, division.
- **Clear and Backspace Functionality**: Clear all inputs or delete the last digit.
- **Formatted Numbers**: Outputs are formatted with commas for better readability.
- **Responsive Design**: Designed for various screen sizes.

## File Structure

```
|— .vscode/
|   |— * Visual Studio Code settings files.
|— bgimg.jpg
|   Background image for the calculator.
|— index.html
|   Main HTML file containing the structure of the calculator.
|— style.css
|   CSS file for styling the calculator.
|— script.js
|   JavaScript file containing the functionality of the calculator.
|— README.md
|   Documentation for the project.
```

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url
   ```

2. Open the `index.html` file in any modern web browser.

3. Use the calculator interface to perform calculations:
   - Click on numbers and operators to input calculations.
   - Use the `C` button to clear all input.
   - Use the `CE` button to delete the last entry.
   - The `=` button computes the result.

## Code Explanation

### JavaScript Functions

1. **getHistory()** and **printHistory(num)**
   - Retrieve and display the calculation history.

2. **getOutput()** and **printOutput(num)**
   - Retrieve and display the current output.

3. **getFormattedNumber(num)**
   - Format numbers with commas for readability.

4. **reverseNumberFormat(num)**
   - Convert formatted numbers back to plain numbers for computation.

5. **Event Listeners**
   - Add click event listeners to number and operator buttons to handle user input and perform operations.

### Styling (CSS)

- Buttons are color-coded:
  - Operators (e.g., `+`, `-`, `*`, `/`) have distinct colors for easy identification.
  - `C` and `CE` buttons are styled separately to emphasize their functionality.

## Screenshot

![image](https://github.com/user-attachments/assets/f1fca7a6-9121-445a-bbcf-b643380d2cf7)


## Future Enhancements

- Add scientific calculator features such as trigonometric functions.
- Improve accessibility with keyboard support.
- Add a dark mode toggle.

## License

This project is open source and available under the [MIT License](LICENSE).


