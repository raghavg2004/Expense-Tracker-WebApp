# Expense Tracker

This is a simple web-based **Expense Tracker** that allows users to track their income and expenses. The application also supports **dark mode** and saves the user's data using **localStorage**, ensuring that all entries are retained even after the browser is closed and reopened.

## Features

- **Add Income/Expense**: Users can input the name, amount, and type (income or expense) of their financial entries.
- **Real-Time Balance Calculation**: Automatically updates and displays the total income, total expenses, and the remaining balance.
- **Dark Mode Toggle**: Easily switch between light and dark themes.
- **Persistent Data**: All data is saved in `localStorage`, ensuring that your entries are saved and available even after closing or refreshing the browser.
- **Delete Entries**: Users can remove entries, with the balance and totals automatically updating.

## Technologies Used

- **HTML**: Structure and content of the web app.
- **CSS**: Styling for the layout and the dark mode feature.
- **JavaScript**: Handles the application logic such as adding, deleting, calculating totals, and saving/loading data in `localStorage`.

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/raghavg2004/Expense-Tracker-WebApp.git
    ```

## Usage

1. **Adding Entries**:
   - Use the "Add new" section to input the name, amount, and type (Income or Expense) of your financial entry.
   - Click the **Add** button to add it to the table and update the totals.

2. **Deleting Entries**:
   - Click the red ❌ button next to any entry to delete it.
   - The totals and balance will automatically update.

3. **Dark Mode**:
   - Toggle the **Dark Mode** switch to change the theme of the application.

4. **Data Persistence**:
   - Your data is saved locally in your browser's `localStorage`. Whenever you reopen the app, your previous entries will be automatically loaded.

## Code Structure

- **index.html**: The main structure of the page.
- **style.css**: Contains the styling for the layout, table, and dark mode.
- **script.js**: Handles the logic for adding, deleting, and managing expense/income entries, as well as saving and loading from `localStorage`.

## Future Enhancements

- Add categories for better organization of expenses.
- Provide options to export the data to CSV or Excel.
- Add filtering and sorting functionality to the table.

## License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for more details.
