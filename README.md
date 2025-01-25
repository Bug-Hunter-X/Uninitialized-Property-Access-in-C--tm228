# Uninitialized Property Access in C#

This repository demonstrates a common error in C#: accessing a property that hasn't been explicitly initialized.  This can result in unpredictable behavior, often manifesting as exceptions or unexpected default values.

The `bug.cs` file contains the problematic code. The `bugSolution.cs` file shows how to fix this error.

## How to Reproduce

1. Clone the repository.
2. Compile and run `bug.cs`. Observe the potential exception or unexpected behavior. 
3. Compare to the corrected code in `bugSolution.cs`.