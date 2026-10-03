# Day-116-Copy-List
# Python Day 116 - Copy a List

## Description

This program demonstrates how to use the `copy()` method in Python.

The `copy()` method is used to create a new list containing the same elements as the original list.

## Example

```text
Original list: [10, 20, 30, 40]
Copied list: [10, 20, 30, 40]
```

## Code

```python
numbers = [10, 20, 30, 40]

print("Original list:", numbers)

new_numbers = numbers.copy()

print("Copied list:", new_numbers)
```

## Concepts Used

* Lists
* `copy()` method
* Variables
* `print()`

## How It Works

1. A list named `numbers` is created.
2. The `copy()` method creates a copy of the list.
3. The copied list is stored in `new_numbers`.
4. Both lists contain the same elements.
5. The original and copied lists are displayed.

## Goal

The goal of this program is to understand how to create a copy of a Python list using the `copy()` method.

## File Name

`copy_list.py`
