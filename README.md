# Financial Control Web Application

A web application built in **ASP.NET Core** for managing personal or business finances, providing features such as tracking income and expenses, generating financial reports, and visualizing data with charts.

## Features

- **User Authentication:**
  - Registration, login, and password reset functionality.
  - Security implemented using **ASP.NET Identity**.
  - OAuth authentication via Google, Facebook, etc.
  
- **Dashboard Overview:**
  - A summary view of current financial status including available balance, total income, and total expenses.
  - Interactive graphs showing trends and financial performance.

- **Income and Expense Management:**
  - Add, edit, or delete income and expense records.
  - Categorization of transactions (e.g., "Food", "Transport", "Leisure").
  
- **Custom Categories:**
  - Users can create their own categories for better financial organization.
  
- **Financial Reports:**
  - Generate monthly, quarterly, or yearly financial reports.
  - Visualized using **Chart.js** graphs.

- **Notifications and Reminders:**
  - Set reminders for upcoming payments or incomes.

## Technology Stack

- **Backend:**
  - [ASP.NET Core](https://dotnet.microsoft.com/apps/aspnet) (MVC Architecture).
  - [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) for database interactions.
  
- **Frontend:**
  - * **Bootstrap** for a responsive and user-friendly interface.

- **Database:**
  - **SQL Server** with Entity Framework for data persistence.


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/financial-control-app.git
    ```
   
2. Navigate to the project directory:
    ```bash
    cd financial-control-app
    ```
    
3. Install the required NuGet packages:
    ```bash
    dotnet restore
    ```

4. Apply migrations and update the database:
    ```bash
    dotnet ef database update
    ```

5. Run the application:
    ```bash
    dotnet run
    ```

6. Access the application via the browser:
    ```
    http://localhost:5000
    ```

