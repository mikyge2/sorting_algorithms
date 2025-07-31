# Sorting Algorithms

This repository contains implementations of various sorting algorithms in C, built for educational purposes and algorithmic practice.

## Table of Contents

* [Overview](#overview)
* [Algorithms Implemented](#algorithms-implemented)
* [File Structure](#file-structure)
* [How to Compile and Run](#how-to-compile-and-run)
* [Usage Examples](#usage-examples)
* [Requirements](#requirements)
* [Author](#author)

## Overview

Sorting is a fundamental concept in computer science. This project demonstrates how various sorting techniques are implemented in C, including classic algorithms like Bubble Sort, Insertion Sort, Merge Sort, and more complex ones such as Radix Sort, Bitonic Sort, and Quick Sort using the Hoare partition scheme.

Each algorithm is implemented in its own `.c` file for clarity and modularity.

## Algorithms Implemented

| Algorithm            | File Name                  |
| -------------------- | -------------------------- |
| Bubble Sort          | `0-bubble_sort.c`          |
| Insertion Sort       | `1-insertion_sort_list.c`  |
| Shell Sort           | `100-shell_sort.c`         |
| Cocktail Shaker Sort | `101-cocktail_sort_list.c` |
| Counting Sort        | `102-counting_sort.c`      |
| Merge Sort           | `103-merge_sort.c`         |
| Heap Sort            | `104-heap_sort.c`          |
| Radix Sort           | `105-radix_sort.c`         |
| Bitonic Sort         | `106-bitonic_sort.c`       |
| Quick Sort (Hoare)   | `107-quick_sort_hoare.c`   |
| Selection Sort       | `2-selection_sort.c`       |
| Quick Sort           | `3-quick_sort.c`           |

## File Structure

* `deck.h` – Header for doubly linked list nodes (used in deck sorting).
* `main.c`, `main2.c` – Test files.
* `print_array.c`, `print_list.c` – Helper functions to print arrays and lists.
* `sort.h` – Common function prototypes and structures.
* `README.md` – This file.

## How to Compile and Run

Use `gcc` to compile the programs. Example:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 0-bubble_sort.c print_array.c main.c -o bubble
./bubble
```

Each `.c` file typically requires linking to `print_array.c` or `print_list.c`, depending on whether the algorithm works on arrays or lists.

## Usage Examples

To run a specific sorting algorithm:

1. Compile it with the appropriate helpers:

   ```bash
   gcc 3-quick_sort.c print_array.c main.c -o quick
   ```

2. Run the executable:

   ```bash
   ./quick
   ```

Modify `main.c` as needed to test specific arrays or data structures.

## Requirements

* Ubuntu 20.04+ or equivalent Linux distro
* GCC Compiler
* C Standard: `gnu89`

## Author

**Mikyge2**

> GitHub: [@mikyge2](https://github.com/mikyge2)
