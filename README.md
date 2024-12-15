# F# Mutable Variable Swap Bug

This repository demonstrates a subtle issue involving mutable variables and shadowing in F#.  The `swap` function attempts to swap the values of two mutable variables, but due to how F# handles variable scoping, it doesn't work as intuitively expected.

The `bug.fs` file contains the problematic code. The `bugSolution.fs` file provides a corrected version using different techniques.

This example highlights the importance of understanding F#'s scoping rules when working with mutable variables.  While mutability is generally discouraged in functional programming, this example shows how unexpected behavior can occur even when using mutable features.