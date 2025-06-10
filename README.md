# Algorithm-efficiency

# Algorithm Efficiency and Scalability

## Overview

This repository contains the implementation and performance analysis of two sorting algorithms: **Randomized Quicksort** and **Deterministic Quicksort**. It also includes a **Hash Table** implementation using **Chaining** for collision resolution. The goal of this project is to analyze the efficiency of these algorithms under various input conditions and observe the results.

### Algorithms Implemented:
1. **Randomized Quicksort**:
   - A variation of the classic Quicksort algorithm where the pivot is chosen randomly to prevent worst-case performance on already sorted or reverse-sorted data.
   
2. **Deterministic Quicksort**:
   - A traditional Quicksort algorithm where the pivot is always the first element of the array. This version can degrade to worst-case performance (\(O(n^2)\)) on sorted or reverse-sorted data.
   
3. **Hash Table with Chaining**:
   - A hash table that uses chaining (linked lists) to handle collisions. Operations like insert, search, and delete are implemented efficiently with a good hash function.

---

## Files in This Repository:

- **`randomized_quick_sort.py`**: Python implementation of the Randomized Quicksort algorithm.
- **`deterministic_quick_sort.py`**: Python implementation of the Deterministic Quicksort algorithm.
- **`hash_table_chaining.py`**: Python implementation of the Hash Table using Chaining.
- **`report.docx`**: A detailed report containing the theoretical analysis, empirical comparisons, and discussion of results.
- **`README.md`**: Instructions for running the code and a summary of the findings.

---

## How to Run the Code:

### Prerequisites:
- Python 3.x should be installed on your system.

### Running the Sorting Algorithms:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/nkannekanti38720/algorithm-efficiency.git
