# Tcl proc with Potential Division by Zero Error

This repository demonstrates a common error in Tcl: unhandled division by zero in a procedure. The `bug.tcl` file contains the buggy code, while `bugSolution.tcl` provides the corrected version.

## Bug Description

The `badproc` procedure in `bug.tcl` does not check for the case where the first argument (`a`) is zero, which will result in a runtime error if the procedure is called with `a = 0`. 

## Solution

The solution, found in `bugSolution.tcl`, adds a check to handle this case, preventing the division by zero error.