# Windows Forms App for SQL Database Operations

![ab](https://github.com/SyedNoorAliDev/.NET-SQL-App/assets/96229280/8ce10395-f517-44d4-8439-310ffc5ce2d2)

This simple Windows Forms application allows you to perform basic SQL database operations such as connecting to a database, retrieving records, counting records, and inserting records. It is a great starting point for learning how to work with databases in C# using the Windows Forms framework.

## Features

- **Connection Test:** Verify your database connection to ensure it's successful.
- **Retrieve Records:** Fetch records from the database and display them in a DataGridView.
- **Count Records:** Get the count of records in a table.
- **Insert Records:** Insert new records into the database.

## Prerequisites

Before you begin, make sure you have the following:

- Visual Studio or another C# development environment.
- SQL Server (SQL Express or other editions) installed on your machine.
- A SQL database (in this example, we're using the Northwind sample database).

## Getting Started

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Open the project in Visual Studio or your preferred C# development environment.

3. Build and run the application.

## Usage

1. **Connect to Database:** On application startup, the program will attempt to connect to the Northwind database. The connection status will be displayed in the textbox labeled "Status."

2. **Retrieve Records:** Click the "Retrieve Records" button to fetch records from the "Customers" table in the Northwind database and display them in the DataGridView.

3. **Count Records:** Click the "Count Records" button to determine the number of records in the "Customers" table.

4. **Insert Records:** Enter values in the "CustomerID" and "CompanyName" textboxes, then click the "Insert Record" button to add a new customer to the "Customers" table.

## Troubleshooting

If you encounter any issues with the application, please check the following:

- Ensure that you have SQL Server installed and running.
- Verify that you have the Northwind sample database installed, or adjust the connection string in the code to match your database.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [Microsoft](https://www.microsoft.com) for providing the Northwind sample database.
- This project was inspired by the need for a simple example of Windows Forms database integration.

