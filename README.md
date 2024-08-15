# Budget Buddies (PHP)

**Budget Buddies** is a PHP-based application designed to help users manage their daily finances efficiently. With features like budget setting, expense tracking, and detailed reporting, Budget Buddies provides a comprehensive solution for personal financial management.

## Key Features

### 1. User Registration & Login
- **Easy Sign-Up**: New users can quickly register and create an account.
- **Secure Login**: Registered users can log in securely to access their personal dashboard.

### 2. User Dashboard
- **Personalized View**: After logging in, users can view their overall budget, recent expenses, and account settings.
- **Secure Password Management**: Users can update their passwords to ensure account security.

### 3. Set Budget
- **Category-Based Budgeting**: Define budgets for different expense categories (e.g., groceries, entertainment) and monitor spending within these limits.

### 4. Add/Manage Expenses
- **Input Transactions**: Easily add details of each expense, including amount, category, and date.
- **Manage Transactions**: View, edit, or delete transactions with real-time updates to the budget.

### 5. Expense Report
- **Generate Reports**: Create detailed reports based on selected date ranges to analyze spending patterns.
- **Export Options**: Export reports for further analysis or record-keeping.

### 6. Expense Graph
- **Visualize Spending**: Interactive graphs display spending patterns, helping users identify trends and manage their finances better.

## How to Run the Project

### 1. Set Up the Database
- **Step 1**: Open phpMyAdmin.
- **Step 2**: Create a new database named `expenseman`.
- **Step 3**: Import the SQL file located in the `DATABASE FILE` folder (`expenseman.sql`) into the newly created database.

### 2. Run the Project
- **Step 1**: After setting up the database, open your web browser.
- **Step 2**: Navigate to the following URL: `http://localhost/expense-tracker/` to access the application.

## Folder Structure

```
budget-buddies/
│
├── assets/               # Contains CSS, JS, and image files
├── includes/             # Common includes like header, footer, and database connection
├── user/                 # User-facing pages for dashboard, expenses, and reports
├── config.php            # Database configuration file
├── index.php             # Entry point of the application
├── DATABASE FILE/        # Folder containing the SQL file for database setup
└── README.md             # Project documentation
```

## Prerequisites

Before running the project, make sure your environment meets the following requirements:
- **PHP** (>= 7.0)
- **MySQL** (>= 5.7)
- **Web Server** (e.g., Apache) configured to run PHP applications.

## Troubleshooting

- **Database Connection Issues**: Ensure your `config.php` file has the correct MySQL credentials and that your MySQL server is running.
- **File Permissions**: On some servers, you may need to adjust file permissions to ensure the web server can read/write files.
- **PHP Errors**: Enable error reporting in PHP to debug issues. Add the following to the top of your `index.php` file:
  ```php
  error_reporting(E_ALL);
  ini_set('display_errors', 1);
  ```

## Contributing

If you would like to contribute to Budget Buddies, please fork the repository and submit a pull request with your improvements. 

## License

This project is open-source and available under the MIT License.
