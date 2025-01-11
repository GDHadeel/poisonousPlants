# Poisonous Plants Problem

## Description
This repository contains a Java implementation of the **Poisonous Plants Problem**, which simulates the survival of plants based on their pesticide levels. The goal is to determine the maximum number of days until no plants die.
- Problem: The problem involves determining how many days plants will take to stabilize based on their pesticide levels. Each day, plants with a higher pesticide level than the plant to their left will die. The simulation continues until no plants die.

## Features

- Calculates the maximum number of days until plant stabilization.
- Efficient stack-based approach for simulating the survival process.
- JavaFX GUI with a basic **Welcome Screen**.

## Code Overview

### Files:
- **`plantsLife.java`**:  
  The main class containing the logic for processing plant pesticide levels.

- **`HelloController.java`**:  
  JavaFX controller for the basic GUI with a "Welcome to JavaFX Application!" message.

- **`plants.java`**:  
  Contains the `Stk` class, a custom stack implementation used for handling plant indices and operations.

## Key Functions in `plantsLife.java`:

- **`main(String[] args)`**:  
  Entry point for the program. Reads input and calls the `process` method.

- **`process(int[] a)`**:  
  Core logic for calculating the number of days for stabilization using a custom stack.

- **`getMax(int[] maxK, int start, int end)`**:  
  Utility function to get the maximum value in a subarray.

## Example Input/Output
### Input:
```
5
6 5 8 4 7
```
### Output:
```
2
```
### Explanation:
- Day 1: Plants with pesticide levels `8` and `7` die.
- Day 2: Plant with pesticide level `6` dies.


