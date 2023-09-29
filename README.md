# Docmet
# DocMet - Online Doctor Appointment Booking System

![DocMet Logo](docmet-logo.png)

Welcome to DocMet, an online doctor appointment booking system that allows users to easily schedule appointments with healthcare professionals. DocMet is built using HTML, CSS, JavaScript, PHP, and MySQL to provide a responsive and user-friendly experience. This README file will guide you through the key features and setup of DocMet.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Database](#database)
7. [Contributing](#contributing)
8. [License](#license)

## 1. Introduction

DocMet simplifies the process of booking medical appointments. Users can create accounts, search for healthcare providers, view their availability, and book appointments—all without any payment requirements. This system aims to make healthcare access more convenient and accessible.

## 2. Features

- **User Registration**: Users can create accounts by providing basic information.
- **Search for Doctors**: Users can search for healthcare professionals based on specialization, location, and other criteria.
- **View Doctor Profiles**: Users can view detailed profiles of healthcare providers, including their qualifications and availability.
- **Book Appointments**: Users can book appointments with doctors of their choice based on the available time slots.
- **Responsive Design**: DocMet is designed to work seamlessly on various devices, including desktops, tablets, and smartphones.

## 3. Prerequisites

Before you get started with DocMet, ensure you have the following prerequisites:

- Web server (e.g., Apache)
- PHP (>= 7.0) and MySQL installed and configured
- Basic knowledge of HTML, CSS, JavaScript, PHP, and MySQL
- A modern web browser

## 4. Installation

1. Clone the DocMet repository to your web server's root directory:

   ```bash
   git clone https://github.com/yourusername/docmet.git
   ```

2. Create a MySQL database and import the provided `docmet.sql` file to set up the database schema.

3. Modify the database configuration settings in `config.php` to match your database credentials:

   ```php
   define('DB_SERVER', 'PHP/MYADMIN');
   define('DB_USERNAME', 'Amit');
   define('DB_PASSWORD', 'Amit');
   define('DB_NAME', 'myhmsdb');
   ```

4. Start your web server and navigate to the DocMet URL in your web browser.

## 5. Usage

1. **User Registration**: Register for a new account on the DocMet website.

2. **Login**: Use your credentials to log in to your account.

3. **Search for Doctors**: Use the search feature to find doctors based on specialization, location, or other criteria.

4. **View Doctor Profiles**: Click on a doctor's profile to view detailed information, including their schedule.

5. **Book Appointments**: Select an available time slot to book an appointment with your chosen doctor.

6. **Manage Appointments**: View and manage your upcoming appointments from your account dashboard.

7. **Logout**: Log out of your account when you're done.

## 6. Database

DocMet uses MySQL to store user data, doctor information, and appointment records. You can find the database schema in the `docmet.sql` file, which you should import into your MySQL database to set up the necessary tables.

## 7. Contributing

If you would like to contribute to DocMet or report issues, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## 8. License

DocMet is released under the [MIT License](LICENSE). Feel free to use, modify, and distribute this system for your needs, but please provide appropriate attribution and adhere to the license terms.

Thank you for using DocMet! We hope it serves as a valuable tool for simplifying doctor appointment booking and improving access to healthcare services. If you have any questions or feedback, please don't hesitate to reach out to us.
