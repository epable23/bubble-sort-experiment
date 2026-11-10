Bubble Sort Experiment Reproduction

Overview

This package contains all the source code, raw data, and statistical analysis used for Experiment 1: Bubble Sort Algorithm Library.

Source Code & Files

- src/exp01/ – Contains the Java source code for the three Bubble Sort implementations, the Sorter interface, and ExperimentRunner.
- results/measurements.csv – Raw data file containing 270 execution-time measurements.
- BubbleSort_Analysis.xlsx – Spreadsheet containing the statistical analysis and plots used in the experimental report.

Experimental Parameters

- Programming Language: Java
- Java Version: OpenJDK 21.0.6 LTS
- Array Sizes: 100, 500, 1,000
- Input Types: Sorted, Random, Reversed
- Repetitions: 10 per condition
- Warm-up Runs: 5 per algorithm
- Total Measurements: 270

Executing the Experiment

Compile the Java source code and run the ExperimentRunner class to execute the experiment and generate the measurements CSV file.

Data Analysis

The Excel file contains the descriptive statistics and plots used to produce the results presented in the report.