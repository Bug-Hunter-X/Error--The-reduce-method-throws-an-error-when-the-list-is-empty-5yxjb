# Dart Reduce Method Error

This repository contains a bug and its solution related to the Dart `reduce` method. The bug arises when the `reduce` method is called on an empty list, resulting in an error. The solution demonstrates how to handle this scenario gracefully.

## Bug

The `reduce` method, used to apply a function cumulatively to the elements of a list, throws a `StateError` when applied to an empty list. This is because the method requires at least one element to perform the reduction.

## Solution

The solution involves adding a check to ensure the list is not empty before calling `reduce`. If the list is empty, a default value (e.g., 0) is returned. This prevents the error and provides a more robust solution.

## Usage

1. Clone the repository.
2. Open the `bug.dart` and `bugSolution.dart` files. 
3. Run the files using a Dart compiler or IDE.