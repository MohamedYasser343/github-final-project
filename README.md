# Simple Interest Calculator

A bash script to calculate simple interest based on principal amount, rate of interest, and time period.

## Description

This project provides a simple command-line tool for calculating simple interest. It's designed to help individuals, particularly those in micro-finance, quickly compute interest on loans or investments.

The calculator uses the standard simple interest formula:

```
Simple Interest = (Principal × Rate × Time) / 100
```

## Features

- Interactive command-line interface
- Calculates simple interest based on user input
- Clear display of all parameters and results
- Lightweight and easy to use

## Requirements

- Bash shell
- `bc` calculator (for floating-point arithmetic)

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. Make the script executable:
   ```bash
   chmod +x simple-interest.sh
   ```

## Usage

Run the script:

```bash
./simple-interest.sh
```

Follow the prompts to enter:
- Principal amount
- Rate of interest (in percentage)
- Time period (in years)

The script will calculate and display the simple interest.

## Example

```
Simple Interest Calculator
==========================

Enter the principal amount: 1000
Enter the rate of interest (in %): 5
Enter the time period (in years): 2

Principal Amount: 1000
Rate of Interest: 5%
Time Period: 2 years
Simple Interest: 100.00
```

## Contributing

We welcome contributions from the community! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## Code of Conduct

This project adheres to a Code of Conduct that all contributors are expected to follow. Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please open an issue in the repository.

## Author

Developed as part of a micro-finance initiative to empower and provide opportunities to low-income individuals.
