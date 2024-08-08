# phase-2-code-challenge-1


# Flatiron Bank Transaction Management App

## Overview

This React application called the Transaction Management App is used to track and handle transactions. A list of transactions can be seen by users, who can also add new ones, filter, sort, and remove items. A thorough how-to for installing, utilizing, and contributing to the project is provided in this README.



## Features

- **View Transactions:** Display a table of all transactions.
- **Add Transactions:** Fill out and submit a form to add new transactions.
- **Filter Transactions:** Use a search bar to filter transactions by description.
- **Sort Transactions:** Sort transactions by category or description.
- **Delete Transactions:** Remove transactions from the table.

## Setup and Installation

### Prerequisites

- [Node.js](https://nodejs.org/) and npm (Node Package Manager) installed on your machine.
- [json-server](https://www.npmjs.com/package/json-server) installed globally to serve the JSON data.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone <git@github.com:alvinsarisar/weekend-3-code-challenge.git>
   cd bank/of/flatiron

  ## Usage of the app

### 1.Viewing Transactions

A table of every transaction retrieved from the JSON server is shown on the main page.


### 2.Adding a Transaction

To add a new transaction:
1. **First Fill out the form** located at the top of the page.
2. **Providing  the following details into the available prompt menus**:
   - **Date**: Select a date from the date the transaction took place.
   - **Description**: Enter a brief description of the transaction.
   - **Category**: Enter the transaction category (e.g., Food, Transportation, income, entertainment  etc).
   - **Amount**: Enter the transaction amount (Remember to include positive for income and  negative for expenses).
3. **Click the "Add Transaction" button**.
4. The new transaction will appear in the table but will not be persisted to the backend.

### Filtering Transactions

To filter transactions:
1. **Use the search bar** located above just immediately the transactions table.
2. **Type a keyword** from the description of the transactions you want to view.It must be available in the form table
3. The table will automatically update to display only transactions that match the search term.


### Deleting a Transaction

To delete a transaction:
1. **Locate the transaction** you wish to remove in the transactions table.
2. **Click the "Delete" button** next to the transaction.
3. The transaction will be removed from the table.

## Project Structure

The project consists of the following key components:

- **`App.js`**: 
  - The main component that holds the state and renders other components.
  
- **`TransactionsTable.js`**: 
  - Displays a table of transactions.
  
- **`AddTransactionForm.js`**: 
  - A form to add new transactions.
  
- **`SearchBar.js`**: 
  - A search bar to filter transactions.
  
- **`styles.css`**: 
  - Contains styling for the application, including the form, table, and buttons.
  
- **`index.js`** (or **`main.jsx`** in Vite setup):
  - The entry point of the application that renders the `App` component into the DOM.

- **`db.json`**:
  - A JSON file containing sample transaction data used by the JSON server.
  
- **`README.md`**:
  - Documentation for the project, including setup instructions, usage, and contribution guidelines.
**
