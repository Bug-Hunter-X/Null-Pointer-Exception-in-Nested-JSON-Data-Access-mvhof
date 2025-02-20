# Dart - Null Pointer Exception in Nested JSON Data Access

This repository demonstrates a common error in Dart when handling nested JSON data: null pointer exceptions due to missing null checks.

The `bug.dart` file contains code that attempts to access a deeply nested JSON value without checking if intermediate levels are null.  This can lead to runtime errors if the JSON structure doesn't match the expected format.

The `bugSolution.dart` file demonstrates a corrected version with appropriate null checks, preventing the exception.