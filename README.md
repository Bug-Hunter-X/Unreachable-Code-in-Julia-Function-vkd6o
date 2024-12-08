# Unreachable Code in Julia
This repository demonstrates a common coding error in Julia: unreachable code.  The `bug.jl` file contains a function with a return statement that will never be executed. This can lead to unexpected behavior and reduced code readability. The `bugSolution.jl` file provides a corrected version.

## How to reproduce
1. Clone this repository.
2. Run `bug.jl` (the code may produce a warning) 
3. Compare its behavior with `bugSolution.jl`