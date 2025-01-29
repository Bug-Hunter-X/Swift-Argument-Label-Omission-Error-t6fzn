# Swift Argument Label Omission
This repository demonstrates a common error in Swift: forgetting to include argument labels when calling functions.  Swift's type system relies on argument labels for clarity and to prevent ambiguity.  The `bug.swift` file contains the erroneous code, while `bugSolution.swift` shows the corrected version.

## How to Reproduce
1. Clone this repository.
2. Open `bug.swift` in Xcode.
3. Try to compile the code. You will receive a compiler error indicating that the argument label is missing.

## Solution
Always include argument labels when calling functions to maintain code clarity and avoid errors. See `bugSolution.swift` for the corrected code.