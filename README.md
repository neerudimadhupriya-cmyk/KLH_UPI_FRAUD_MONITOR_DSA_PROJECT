# KLH_UPI_FRAUD_MONITOR_DSA_PROJECT
# PROJECT TITLE: SAFEPAY: UPI FRAUD MONITOR

**TEAM NO:** KLH/PSPJ/S14/T6

## TEAM MEMBERS:

2620080072 - Madhu Priya  
2620090149 - Deeksha

**SUPERVISOR:** Dr. Chaitnya kumar

## Abstract

SafePay: UPI Fraud Monitor is a fintech-based project designed to analyse digital payment transactions and identify potentially suspicious patterns using fundamental data structures and algorithms. The system processes transaction details such as account number, transaction time, amount, and merchant to detect duplicate transactions, unusual transaction bursts, and patterns that may indicate fraudulent activity.

The project implements six algorithmic milestones: duplicate transaction detection using hashing and counting, backtracking to identify combinations of transfers matching a flagged amount, prefix sums to detect consecutive transaction runs, sliding windows to find the shortest burst of transactions reaching a specified amount, binary search to count transactions within a given time interval, and deque-based sliding window maximum to identify the highest transaction amounts within a fixed window. These algorithms demonstrate efficient transaction analysis and the practical application of algorithmic problem-solving techniques.

The system uses synthetically generated transaction data to ensure consistent and reproducible testing. It also compares brute-force and optimized approaches using operation counts and time complexity analysis to evaluate performance on increasing input sizes. Automated tests verify the correctness of each algorithm and handle edge cases. The project is developed progressively over 12 weeks, applying concepts such as arrays, strings, hashing, recursion, backtracking, prefix sums, sliding windows, binary search, sorting, stacks, queues, and collections. SafePay demonstrates how fundamental programming concepts can be applied to financial transaction monitoring and provides a foundation for future extensions involving advanced anomaly detection and suspicious-account ranking.

## PROJECT STRUCTURE

```text
SafePay-UPI-Fraud-Monitor/
│
├── src/
│   ├── Main.java
│   ├── Transaction.java
│   ├── TransactionGenerator.java
│   ├── DuplicateDetector.java
│   ├── BacktrackingAnalyzer.java
│   ├── PrefixSumAnalyzer.java
│   ├── SlidingWindowAnalyzer.java
│   ├── BinarySearchAnalyzer.java
│   ├── DequeWindowAnalyzer.java
│   └── PerformanceAnalyzer.java
│
├── README.md
├── data/
└── reports/
```

## EXECUTION INSTRUCTIONS

1. Install the Java Development Kit (JDK 11 or later) and configure Java on your system.
2. Open the project folder in Visual Studio Code or Command Prompt.
3. Save the Java source files inside the `src` folder.
4. Navigate to the source folder using Command Prompt:

   ```bash
   cd src
   ```

5. Compile the Java files:

   ```bash
   javac *.java
   ```

6. Run the program:

   ```bash
   java Main
   ```

7. Follow the console instructions to execute the transaction analysis, automated tests, and performance comparisons.

**Note:** The project structure above is a proposed structure. The commands assume that all Java files are stored directly inside `src` and that `Main.java` contains the main method.

## GIT COMMANDS

### Initial project setup

```bash
git init
git add .
git commit -m "Initial project setup"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

### For future updates

```bash
git add .
git commit -m "Updated SafePay fraud monitor"
git push
```

## KEY FEATURES

- Duplicate transaction detection using hashing and counting.
- Combination analysis using backtracking.
- Consecutive transaction analysis using prefix sums.
- Detection of rapid transaction bursts using sliding windows.
- Transaction time-range queries using binary search.
- Rolling maximum transaction analysis using a deque.
- Brute-force versus optimized algorithm comparison.
- Automated test cases and edge-case validation.
- Synthetic transaction data generation for reproducible testing.
- Performance measurement using operation counts and Big-O analysis.

## TECHNOLOGIES USED

- **Programming Language:** Java
- **JDK Version:** Java 11 or later
- **Core Concepts:** Data Structures and Algorithms
- **Development Environment:** Visual Studio Code
- **Version Control:** Git and GitHub

## FUTURE ENHANCEMENTS

- Detect abnormal spending patterns using Kadane's algorithm.
- Rank suspicious accounts using a priority queue or heap.
- Add transaction history storage and report export.
- Extend the system with machine learning-based anomaly detection.
- Develop a graphical user interface for easier interaction.

**Disclaimer:** SafePay is an educational prototype that analyses synthetic transaction data. It demonstrates fraud-monitoring techniques but does not connect to live UPI networks or independently confirm actual fraud.
