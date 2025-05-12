# Personal Finance Mobile Application

### Features

* **Splash Screen**: Displays a welcome message and introduction to the app.
* **Login**: Secure user authentication with fields for email and password.
* **Registration**: Create a new user with fields for name, email, phone number, and password.
* **Dashboard**: View a summary of financial details including balance, income, and expenses.
* **Transactions**: Add or delete transactions to track financial activity.
* **Wallets**: Manage multiple wallets by adding or deleting them.
* **Statistics**: View graphs and statistics of income, expenses, and overall financial health.
* **Notifications**: Stay updated with notifications for significant changes in finances or alerts.

### Technologies Used

* **Programming Language**: Kotlin
* **XML**: For creating layouts and UI components
* **Android Studio**: For development and testing
* **Firebase (Optional)**: For backend database (authentication, storage, etc.)


## Functionalities and Components

### 1. **Splash Screen**

* A welcome screen that provides an introduction to the app.

### 2. **Login**

* User authentication to log into the application using email and password.
* Data validation for login credentials.

### 3. **Registration**

* Create a new account by entering personal details like name, email, phone, and password.
* Validation to ensure all fields are correctly filled.

### 4. **Dashboard**

* Displays financial summary such as balance, income, and expenses.
* Action buttons to add or delete wallets, transactions, and view statistics.

### 5. **Add/Delete Transaction**

* Users can add or delete transactions related to income and expenses.
* Fields include amount, date, description, and transaction type.

### 6. **Add/Delete Wallet**

* Users can manage multiple wallets.
* Add or delete wallets to track finances in different accounts.

### 7. **Statistics**

* Displays graphical charts and statistics to visualize income, expenses, and overall balance.
* Provides insights into the financial health of the user.

### 8. **Notifications**

* The app sends notifications for significant events such as balance updates or reminders to add transactions.

## How to Use the App

1. **Splash Screen**: Wait for the splash screen to load.
2. **Login/Registration**: Enter your credentials to log in or create a new account.
3. **Dashboard**: Once logged in, you'll be redirected to the dashboard, where you can manage your finances.
4. **Transactions**: Add or remove transactions by clicking the respective buttons.
5. **Wallets**: Manage your wallets and keep track of balances by adding or deleting wallets.
6. **Statistics**: View your financial statistics to track your spending and income trends.
7. **Notifications**: Receive timely updates for any important events in your finances.

## Troubleshooting

* **App Crashes on Launch**: Ensure all dependencies are correctly added and that the app is properly synced with Gradle.
* **Transaction Data Not Saving**: Double-check your database setup (if using Firebase or another backend) and ensure data is being written to the correct path.
* **Slow Performance**: If the app feels slow, try optimizing the layout with **ConstraintLayout** or check for unnecessary operations on the main thread.


