# Expense Tracker Assignment

Create a simple Expense Tracker built with React and TypeScript.
## Step 1
Step one can be started after the TodoList is implemented in the course

### Features
- Add expenses with description, amount, type (income/outcome), and date
- Validation to ensure all fields are filled and the amount is a valid number
- View a list of all expenses in a table
- Delete expenses
- Type-safe code using TypeScript

**Note:** If the selected type is **outcome**, the amount should be saved as a negative value.

### Usage
1. Enter a description, amount, date, and select the type (income or outcome).
2. Click **Add Expense** to add it to the table.
3. View all expenses in the table below. Use the **Delete** button to remove an expense.

![Expense tracker](./src/assets/screenshot.png)

### Bonus
- Display the current saldo (total balance) on the page, calculated as the sum of all expense amounts.
- Monthly limit and alert.

## Step 2
Step two can be started after the Material UI is studied in the course. In this phase you'll enhance the Expense Tracker by using the Materia UI components.

**Material UI component:**
- Create an app bar for the application that show the header text Expense Tracker
- Replace the `input` and `button` elements in the Expense Tracker with suitable Material UI components.
- Input elements and button should be horizontally aligned and add proper spacing and margins between each component to ensure user-friendly ui.

**Date Picker:**
- Replace the current date input field in the Expense Tracker with the MUI-X Date Picker (https://mui.com/x/react-date-pickers/date-picker/).
- In the table where expense entries are listed, format the displayed date in format `yyyy-mm-dd`.

## Step 3
Step three can be started after the MUI-X DataGrid is studied in the course. In this step, you will upgrade the expense list display by replacing the basic HTML table with the MUI-X `DataGrid` component for improved functionality.
Remove the existing HTML table used to display expense entries.

- Implement the MUI-X `DataGrid` component to present the data instead.
- Configure appropriate columns, such as Title, Amount, Date, and any other relevant fields.
- Enable useful features like sorting, filtering, and pagination for better user experience.


