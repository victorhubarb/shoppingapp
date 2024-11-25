# Shopping app <a name="readme-top"></a>
![Static Badge](https://img.shields.io/badge/status-completed-green?style=for-the-badge)

## Introduction
**Shopping app** is a Java application developed to simulate a credit card-based shopping system. The main challenge of the project is to implement features such as managing credit card limits, making purchases, and displaying the list of purchases in ascending order of value. This project emphasizes user input handling, list management, and sorting algorithms.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [Contributors](#contributors)

## Installation

### Prerequisites
- Java JDK 18+ installed
- An IDE such as IntelliJ IDEA, Eclipse, or NetBeans installed

### Steps to run
1. Clone the repository:
   ```bash
   git clone https://github.com/victorhubarb/shoppingapp.git
   cd shoppingapp
   ```
2. Open the project in your preferred IDE:
- Import the project into your IDE (e.g., using “Open Project” in IntelliJ or “Import Project” in Eclipse).
- Ensure the project uses the correct Java SDK (JDK 18+).

3. Run the application:
- Locate the Main class in the project structure.
- Right-click on the Main class and select Run.

## Usage
The application allows users to manage their credit card limit and make purchases through a menu-driven interface. Purchases are stored in a list and displayed in ascending order of value when the user decides to exit. If a purchase exceeds the available limit, the system informs the user and denies the transaction. Here’s an example usage:
	1.	Enter your credit card limit.
	2.	Input the description and value of a purchase.
	3.	Continue making purchases or exit the application.
	4.	On exit, the system displays the list of purchases sorted by value and the remaining credit card balance.

## Features
- **Set Credit Card Limit**: Define the total credit card limit at the start of the session.
- **Make Purchases**: Add purchases by providing a description and value. Each purchase deducts the amount from the available limit.
- **Check Available Balance**: Automatically updates the remaining balance after each successful purchase.
- **Sort Purchases**: Display the list of purchases sorted by value upon exiting.
- **Handle Insufficient Funds**: Notify the user if the purchase exceeds the available credit.

## Technologies
- **Java**

## Contributors
- [Victor Barbosa](https://github.com/victorhubarb)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
