# Basic Banking System

A web application designed to facilitate money transfers between multiple users. This project includes features such as viewing all users, selecting and viewing individual users, transferring money between users, viewing transaction history, and creating dummy users.

## Technologies Used

- **Front-end**: HTML, CSS, Bootstrap, JavaScript
- **Back-end**: PHP
- **Database**: MySQL

## Database Structure

The database contains two tables:

1. **Customers Table**: Stores basic user information including name, email, and current balance.
2. **Transaction Table**: Records all transactions including the sender, receiver, amount, and timestamp.

## Flow of the Website

1. **Home Page**: The landing page of the website.
2. **View all Users**: Displays a list of all users with their basic information.
3. **Select and View One User**: Allows users to select and view detailed information about a specific user.
4. **Transfer Money**: Enables users to transfer money to another user by selecting the recipient and specifying the amount.
5. **Select Receiver**: Allows users to choose the recipient from the list of all users.
6. **View Transfer History**: Provides users with access to view the transaction history, including details of past transactions.

## How to Use

1. Clone the repository to your local machine.
2. Import the MySQL database schema provided in the project.
3. Configure the database connection in the PHP files.
4. Run the project by opening the `index.php` file in your web server environment.
5. Follow the flow described above to navigate through the website and perform various actions.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or create a pull request.


