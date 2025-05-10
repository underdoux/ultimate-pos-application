
Built by https://www.blackbox.ai

---

# Ultimate POS

Ultimate POS is a Point of Sale (POS) application developed by [Ultimate Fosters](http://ultimatefosters.com), a brand of [The Web Fosters](http://thewebfosters.com). This application is designed to cater to various business needs, offering robust features for a modern sales environment.

## Project Overview

The Ultimate POS application is built on the Laravel framework and incorporates a variety of functionalities for managing sales processes. It supports several modules such as Accounting, Ecommerce, and Inventory Management, providing a comprehensive solution tailored for business operations.

## Installation

To install Ultimate POS, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/[YOUR_USERNAME]/ultimate-pos.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ultimate-pos
   ```
3. Run the composer install command to install the dependencies:
   ```bash
   composer install
   ```
4. Copy the environment file:
   ```bash
   cp .env.example .env
   ```
5. Generate an application key:
   ```bash
   php artisan key:generate
   ```
6. Set up your database settings in the `.env` file.
7. Run the migrations:
   ```bash
   php artisan migrate
   ```
8. Run the service:
   ```bash
   php artisan serve
   ```

For detailed documentation, you can visit the [online documentation guide](http://ultimatefosters.com/ultimate-pos/).

## Usage

Once the application is running, you can access it via your web browser at `http://localhost:8000`. Log in using your credentials, and start utilizing the features offered by Ultimate POS for your business needs.

## Features

Ultimate POS includes the following modules:

- Essentials
- Accounting
- Asset Management
- CMS (Content Management System)
- Connector
- CRM (Customer Relationship Management)
- Ecommerce
- Field Force
- Manufacturing
- Product Catalogue
- Project Management
- Repair Management
- Spreadsheet Functionality
- Superadmin Panel
- WooCommerce Integration
- AI Assistance
- Hospital Management System (HMS)
- Inbox Reporting
- Custom Dashboard
- Gym Management
- Zatca Integration (KSA)

## Dependencies

The project relies on several key packages and libraries, as specified in `composer.json`. Here are the primary dependencies:

- **PHP**: ^8.0
- **Laravel Framework**: ^9.51
- **Aloha Twilio**: ^4.0
- **GuzzleHTTP**: ^7.2
- **Maatwebsite Excel**: ^3.1.8
- **Stripe PHP**: ^7.122
- **OpenAI PHP**: ^0.4.1
- **Spatie Packages** (e.g., `laravel-backup`, `laravel-permission`, `laravel-activitylog`, etc.)

For a complete list of dependencies, refer to the `composer.json` file.

## Project Structure

Here is an overview of the project's folder structure:

```
ultimate-pos/
│
├── app/                   # Contains application logic
│   ├── Http/              # Controllers and middleware
│   └── other directories...
│
├── database/              # Database migrations and seeds
│   ├── migrations/
│   └── seeders/
│
├── modules/               # Modular structure for features
│   └──...
│
├── tests/                 # Unit and feature tests
│   └──...
│
├── .env                   # Environment configuration file
├── composer.json          # Composer dependencies
└── README.md              # Project documentation
```

## Security Vulnerabilities

If you discover a security vulnerability within Ultimate POS, please send an email to support at [thewebfosters@gmail.com](mailto:thewebfosters@gmail.com). All security vulnerabilities will be promptly addressed.

## License

The Ultimate POS software is licensed under the [Codecanyon license](https://codecanyon.net/licenses/standard).