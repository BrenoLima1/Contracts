# Contracts

This project is a Java application that processes contracts and calculates their installments based on a payment service. It demonstrates the use of object-oriented programming principles such as encapsulation, interfaces, and dependency injection.

## Project Structure

The project is organized into the following packages:

- **`application`**: Contains the main program entry point (`Program.java`).
- **`entities`**: Defines the core domain classes, such as `Contract` and `Installment`.
- **`services`**: Implements the business logic for processing contracts and payment services.

## How It Works

1. The user inputs contract details, including the contract number, date, total value, and the number of installments.
2. The `ContractService` class processes the contract by splitting the total value into installments.
3. The `OnlinePaymentService` interface is used to calculate interest and payment fees for each installment. The `PaypalService` class provides a concrete implementation of this interface.
4. The calculated installments are displayed to the user.

## Key Classes

- **`Contract`**: Represents a contract with a number, date, total value, and a list of installments.
- **`Installment`**: Represents an individual installment with a due date and amount.
- **`ContractService`**: Handles the logic for processing contracts and generating installments.
- **`OnlinePaymentService`**: Interface for payment services, defining methods for calculating fees and interest.
- **`PaypalService`**: Implements the `OnlinePaymentService` interface with specific rules for fees and interest.


## Requirements

- Java 21 or higher
- Eclipse IDE or any Java-compatible IDE

## How to Run

1. Clone the repository or download the project files.
2. Open the project in your IDE.
3. Run the `Program` class located in the `application` package.
4. Follow the prompts in the console to input contract details.

## License
This project is for educational purposes and does not include a specific license.
