# Simple_interest_Calculator

# Simple Interest Calculator

This project is a simple interest calculator designed for microfinance applications. It allows users to calculate simple interest and the total amount after interest is added.

## Features

- Calculate simple interest based on principal, rate, and time.
- Calculate the total amount after adding the calculated interest to the principal.

## Installation

To install the project, clone the repository and install the dependencies using npm:

```bash
git clone <repository-url>
cd simple-interest-calculator
npm install
```

## Usage

To use the Simple Interest Calculator, you can import the `SimpleInterestCalculator` class from the `calculator.ts` file and create an instance of the class. 

### Example

```typescript
import { SimpleInterestCalculator } from './src/calculator';

const calculator = new SimpleInterestCalculator();
const principal = 1000; // Principal amount
const rate = 5; // Interest rate (in percentage)
const time = 2; // Time (in years)

const interest = calculator.calculateInterest(principal, rate, time);
const totalAmount = calculator.calculateTotalAmount(principal, rate, time);

console.log(`Interest: ${interest}`);
console.log(`Total Amount: ${totalAmount}`);
```

## Interfaces

The project defines the following interfaces for type safety:

- **Principal**: Represents the principal amount.
- **Rate**: Represents the interest rate.
- **Time**: Represents the time period for which the interest is calculated.

## License

Aparche 2.0
