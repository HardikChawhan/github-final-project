# Simple Interest Calculator

A simple Bash script to calculate simple interest, created as the first open source project for a micro-finance startup’s transition from SVN to Git.  
This project is intended to help users—especially those from low-income backgrounds—understand and compute simple interest quickly and efficiently via the command line.

## Features

- Calculate simple interest using principal, rate, and time.
- Lightweight, fast, and easy-to-use Bash script.
- Open source and community-friendly.

## Usage

### Requirements

- Bash shell (Linux, macOS, or Git Bash on Windows)

### How to Run

1. **Clone the repository:**

```
git clone https://github.com/<your-username>/simple-interest-calculator.git
cd simple-interest-calculator
```

2. **Make the script executable:**
```
chmod +x simple-interest.sh
```

3. **Run the script:**
```
./simple-interest.sh
```


4. **Follow the prompts:**
- Enter the principal amount.
- Enter the rate of interest (annual, in percent).
- Enter the time period (in years).

The script displays the calculated simple interest and the total amount.

### Example Run

```
$ ./simple-interest.sh
Enter principal amount: 10000
Enter annual interest rate (%): 5
Enter time period (years): 2
Simple Interest: 1000.00
Total amount after 2 years: 11000.00
```


## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for guidelines.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
