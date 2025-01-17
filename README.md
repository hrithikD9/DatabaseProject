# Pharmacy Management System

This project is designed to help pharmacies efficiently manage their inventory, customer details, employee records, and supplier information, as well as track purchases and sales. It is a web-based application built using PHP and MySQL, with a user interface created using HTML5, CSS3, and JavaScript.

## Getting Started

### Installation and Setup

1. Download and install [XAMPP](https://www.apachefriends.org/download.html).
2. Open the XAMPP Control Panel and start Apache and MySQL.
3. Clone this repository to your system or download and extract the zipped folder.
4. Place the `PHARMACY` folder in `C:\xampp\htdocs`.
5. Open `localhost/phpmyadmin` in your web browser.
6. Create a new database named `pharmacy`.
7. Import the `pharmacy.sql` file into the database.

### Launch

1. After importing the database, start the project by navigating to `localhost/PHARMACY/mainpage.php` in your web browser.
2. The Admin Login Page will open by default. Use the following credentials to log in:
	```
	Username: admin
	Password: password
	```

### Demo

For a quick overview of the system, watch the [Demo Video](Project%20Video/DemoView.mp4).

## About the Project

### Introduction

**Pharmacia** is a **Pharmacy Management System** designed to streamline the management of pharmaceutical store records, enhancing efficiency, accuracy, and security. It helps pharmacies maintain details of medicine stock, suppliers, employees, customers, and transactions, replacing manual methods with a more reliable digital system.

### Objectives

The main features of the system include:

- User-friendly interface
- Automation of routine tasks
- Fast search capabilities
- Efficient utilization of time and resources through digitalization
- Generation of alerts and reports on sales and medicines

### Users of the System

The system is intended for use by **Admins** and **Pharmacists**.

#### Admin Capabilities:

- Manage the list of available medicines
- Update supplier information
- Record new stock purchases
- Maintain employee records
- Manage customer details
- Track sales transactions
- Generate and view reports

#### Pharmacist Capabilities:

- View inventory details (price, quantity, etc.)
- Access minimal customer information
- Add new customers
- Record new sales and update the database

## Database Architecture

- **MEDS**: Details of all medicines, including type, quantity, and price.
- **SUPPLIERS**: Information about drug suppliers.
- **PURCHASE**: Records of stock purchases, including order details and delivery dates.
- **EMPLOYEES**: Information about all employees, including Admins, Managers, and Pharmacists.
- **CUSTOMERS**: Customer details for sales transactions.
- **SALES**: Records of all sales, including invoice numbers, customer IDs, employee IDs, total amounts, and sale dates.
- **SALES_ITEMS**: Details of medicines sold in each sale, including invoice numbers, medicine IDs, quantities, and total costs.
- **ADMIN**: Admin login credentials (single record).
- **EMPLOGIN**: Login credentials for all employees except Admin.

## Additional Information

- Review triggers, procedures, and functions for a deeper understanding.
- New employee login details must be added via the database server.
- Admin login details can only be changed through the database server.
- For major changes, please open an *issue* to discuss your proposed modifications.

Feel free to contact us for any further queries.

# DatabaseProject

