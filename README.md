# Groovy NullPointerException Handling in List Iteration

This repository demonstrates a common issue in Groovy when iterating over lists that might contain null values.  The `bug.groovy` file shows how a `NullPointerException` can occur. The `bugSolution.groovy` file demonstrates a better way to handle nulls.

## Problem

The `myMethod` function iterates over a list of integers.  If the list contains a null value, a `NullPointerException` is thrown when the `println` statement tries to access the `number` variable.