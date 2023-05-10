# Calculator Readme

This calculator is a web application that performs basic arithmetic operations like addition, subtraction, multiplication, division, power, square root, and percentage. Additionally, it also has a memory feature where you can store and retrieve a number from memory. 

## How to use

The calculator has two display elements: 
* `previousOperandTextElement` which displays the previous operand and operation, and 
* `currentOperandTextElement` which displays the current operand.

The calculator has the following buttons:
* Number buttons: `0`, `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `.`
* Operation buttons: `+`, `-`, `*`, `/`, `%`, `^`, `√`
* Other buttons: `AC`, `DEL`, `MR`, `M+`, `M-`

### Basic arithmetic operations

To perform a basic arithmetic operation, you should follow the steps below:
1. Click on a number button to enter a number.
2. Click on an operation button to choose the desired operation.
3. Enter the second number by clicking on a number button.
4. Click on the equals button `=` to calculate the result.

### Other operations

* To clear the calculator's display, click the `AC` button.
* To delete the last digit entered, click the `DEL` button.
* To store a number to memory, click the `M+` button.
* To subtract a number from memory, click the `M-` button.
* To retrieve a number from memory and display it on the calculator, click the `MR` button.
* To clear the memory, click the `MC` button.

## Code structure

This calculator is implemented using the object-oriented programming (OOP) paradigm in JavaScript. The Calculator class defines the main functionality of the calculator, including arithmetic operations and memory. 

The calculator's interface is created using HTML and CSS. The calculator's buttons and display elements are accessed using JavaScript's Document Object Model (DOM) API. The calculator's functionality is then bound to these elements using event listeners.

The calculator's code is structured as follows:

* The `Calculator` class that defines the calculator's functionality.
* The `numberButtons`, `operationButtons`, and other variables that store references to the calculator's buttons.
* Event listeners that bind the calculator's functionality to the buttons.

## How to run

To use this calculator, simply copy the code into an HTML file and open it in a web browser. The HTML file should reference the `calculator.css` file for styling and the `calculator.js` file for functionality. You can also use this code in any web development project by copying the relevant parts.
