# Guru-Water-Fastapi
# Inventory Management System

This project is an Inventory Management System that utilizes a modern technology stack to efficiently handle various aspects of inventory management. It provides features to manage vendors, users, Bill of Materials (BOM) lists, and payment processing. The core technologies used in this project are FastAPI, Tortoise ORM, MySQL, and Poetry.

## Features

- **Vendor Management**: Keep track of vendors, their details, and interactions.
- **User Management**: Manage users with appropriate roles and permissions.
- **Bill of Materials (BOM) Lists**: Maintain and update BOM lists for effective inventory tracking.
- **Payment Processing**: Handle payments with accuracy and reliability.

## Technology Stack

- **FastAPI**: A modern, fast web framework for building APIs.
- **Tortoise ORM**: An easy-to-use asyncio ORM inspired by Django.
- **MySQL**: A popular relational database management system.
- **Poetry**: Dependency management and packaging made easy.

## Setup

1. Clone the repository.
2. Install dependencies using Poetry: `poetry install`.
3. Set up MySQL database and update the database configuration in the project settings.
4. Run the application: `poetry run uvicorn main:app --reload`.

## Usage

1. Access the API documentation at `http://localhost:8000/docs`.
2. Use the provided API endpoints to manage vendors, users, BOM lists, and payments.

## Contributions

Contributions to this project are welcome. If you find any issues or want to add new features, please create a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
