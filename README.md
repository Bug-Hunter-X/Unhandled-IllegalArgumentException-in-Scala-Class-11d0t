# Unhandled IllegalArgumentException in Scala

This repository demonstrates a simple Scala class with a potential `IllegalArgumentException` and how to handle it.  The example showcases the importance of proper exception handling to prevent unexpected program crashes.

## Problem

The `MyClass` class sets an age value using a setter method. If a negative age is passed, an `IllegalArgumentException` is thrown. However, the main program does not handle this exception and thus crashes.

## Solution

The solution demonstrates how to handle the exception using a `try-catch` block. This prevents the program from crashing and allows for more graceful handling of invalid input.
