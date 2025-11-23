# Random Number Generator

A simple Python script that generates a random integer within a specified range and simulates a short 'thinking' delay before displaying the result.

---

## 🎯 Purpose

This script serves as a basic demonstration of Python's **`random`** and **`time`** modules. The primary function, `generate_human_like_number`, introduces a 1-second pause (`time.sleep(1)`) before generating the number, creating a slight simulation of a delay or "human-like" thought process.

---

## 🚀 Getting Started

### Prerequisites

You need **Python 3** installed on your system to run this script.

### Installation

No special installation or libraries are required beyond the standard Python installation, as it uses the built-in `random` and `time` modules.

### How to Run

1.  Save the code provided as a file named `number_generator.py`.
2.  Open your terminal or command prompt.
3.  Navigate to the directory where you saved the file.
4.  Run the script using the Python interpreter:

    ```bash
    python number_generator.py
    ```

---

## ⚙️ Function Details

The script contains one main function:

### `generate_human_like_number(min_val=1, max_val=100)`

| Parameter | Default Value | Description |
| :--- | :--- | :--- |
| **`min_val`** | `1` | The lowest possible integer that can be generated (inclusive). |
| **`max_val`** | `100` | The highest possible integer that can be generated (inclusive). |

#### Core Logic

1.  The function prints a message indicating the range being searched.
2.  It uses `time.sleep(1)` to pause execution for 1 second.
3.  It generates a random integer using `random.randint(min_val, max_val)`.
4.  It prints the resulting number.

### Example Usage (as seen in the script)

```python
# Calls the function to generate a number between 1 and 100
generate_human_like_number(1, 100)
