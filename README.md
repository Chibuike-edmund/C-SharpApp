# Food Delivery System README

## Introduction

Welcome to the Food Delivery System, a web application developed using ASP.NET MVC. This system allows users to browse a variety of restaurants, view their menus, place orders, and have delicious food delivered to their doorstep.

## Table of Contents

1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Configuration](#configuration)
4. [Database Setup](#database-setup)
5. [Running the Application](#running-the-application)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Requirements

- Visual Studio 2019 or later
- .NET Core 3.1 or later
- SQL Server (Express or higher)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/food-delivery-system.git
   ```

2. Open the project in Visual Studio.

## Configuration

1. Open the `appsettings.json` file.
2. Configure the connection string in the `DefaultConnection` section to point to your SQL Server instance.

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\MSSQLLocalDB;Database=FoodDeliveryDb;Trusted_Connection=True;MultipleActiveResultSets=true"
},
```

## Database Setup

1. Open the Package Manager Console.
2. Run the following commands to apply migrations and update the database:

   ```bash
   Update-Database
   ```

## Running the Application

1. Press `F5` or click on the "Start" button in Visual Studio to run the application.

## Usage

1. Open your web browser and navigate to `http://localhost:5000` (or another specified port).
2. Browse available restaurants, view their menus, and place orders.
3. Sign up or log in to track your order history.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.