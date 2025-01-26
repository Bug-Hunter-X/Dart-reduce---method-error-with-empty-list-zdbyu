# Dart Reduce() Method and Empty Lists

This repository demonstrates an uncommon error that can occur when using the `reduce()` method in Dart with an empty list.  The `reduce()` method requires at least one element in the list to perform the reduction operation; otherwise, it throws an `UnsupportedError`.

The `bug.dart` file shows the error-causing code, while `bugSolution.dart` provides a solution to handle this scenario gracefully.