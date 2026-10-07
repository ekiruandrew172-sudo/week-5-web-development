# SpendWise Budget Tracker

## Project Description

SpendWise is a simple budget and expense tracking application. It helps users enter their budget information, record an expense, and calculate the amount of money remaining.

The application uses HTML for the structure, CSS for the design, and JavaScript to process user input, perform calculations, and display the results.

## JavaScript Concepts Implemented

The following JavaScript concepts are implemented in the SpendWise project:

* Variables
* Data types
* User input
* `prompt()`
* Type conversion using `parseFloat()`
* Arithmetic calculations
* Functions
* Conditional statements
* DOM manipulation
* `console.log()`

## How Variables Are Used

Variables are used to store important budgeting and expense information.

For example:

```javascript
let budget = 0;
let expenses = 0;
let remainingBalance = 0;

let expenseName = "";
let expenseCategory = "";
```

The `budget` variable stores the total amount of money available.

The `expenses` variable stores the amount spent.

The `remainingBalance` variable stores the amount left after expenses have been deducted.

The `expenseName` and `expenseCategory` variables store information about the expense entered by the user.

## How User Input Is Collected

SpendWise collects user information using JavaScript's `prompt()` function.

The user is asked to enter:

1. Total budget
2. Expense name
3. Expense amount
4. Expense category

Example:

```javascript
budget = parseFloat(
    prompt("Enter your total budget in KSh:")
);

expenseName = prompt(
    "Enter the name of your expense:"
);

expenses = parseFloat(
    prompt("Enter the amount spent in KSh:")
);

expenseCategory = prompt(
    "Enter the expense category:"
);
```

The `parseFloat()` function converts the budget and expense amounts from text into numbers so that calculations can be performed.

## How Calculations Are Performed

SpendWise calculates the remaining balance by subtracting the total expenses from the budget.

The calculation is:

```javascript
remainingBalance = budget - expenses;
```

For example:

```text
Budget = KSh 10,000
Expenses = KSh 2,500

Remaining Balance = KSh 10,000 - KSh 2,500
                  = KSh 7,500
```

The application then displays the calculated remaining balance.

## How Functions Help Organize the Code

Functions help organize the program into smaller and reusable sections.

SpendWise uses the following function to calculate the remaining balance:

```javascript
function calculateRemainingBalance(
    budgetAmount,
    expenseAmount
) {
    return budgetAmount - expenseAmount;
}
```

The function receives the budget and expense amounts as parameters and returns the remaining balance.

Using functions makes the code easier to read, maintain, test, and reuse.

## Displaying Results

The application displays the budget results in the browser console using `console.log()`.

Example:

```javascript
console.log("Total Budget: KSh " + budget.toFixed(2));
console.log("Total Expenses: KSh " + expenses.toFixed(2));
console.log("Remaining Balance: KSh " + remainingBalance.toFixed(2));
```

The results are also displayed on the SpendWise webpage using JavaScript DOM manipulation.

## Project Files

The project contains four main files:

```text
SpendWise/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

### `index.html`

Contains the structure and content of the SpendWise webpage.

### `style.css`

Contains the styling, colors, layout, cards, and responsive design.

### `script.js`

Contains the JavaScript logic for collecting user input, storing data, calculating the remaining balance, and displaying results.

### `README.md`

Contains information about the project, JavaScript concepts used, and instructions for running the application.

## How to Run the Project

1. Download or clone the SpendWise GitHub repository.
2. Open the SpendWise project folder.
3. Make sure all four files are in the same folder.
4. Open `index.html` in a web browser.
5. Enter the requested budget and expense information.
6. View the calculated results on the webpage.
7. Open the browser Developer Tools using **F12**.
8. Select **Console** to view the labeled JavaScript results.

## Testing

The application was tested by:

* Entering different budget amounts.
* Entering different expense amounts.
* Entering different expense names.
* Entering different expense categories.
* Checking the remaining balance calculation.
* Checking the browser console output.
* Checking that `script.js` loads correctly.
* Checking that the results appear correctly on the webpage.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Git
* GitHub

## Submission

The SpendWise project is submitted as a public GitHub repository containing:

* `index.html`
* `style.css`
* `script.js`
* `README.md`

The GitHub repository link will be submitted through the LMS.

## Author

SpendWise Budget Tracker Project

