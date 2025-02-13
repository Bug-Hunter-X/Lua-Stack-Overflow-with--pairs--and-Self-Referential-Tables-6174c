# Lua Stack Overflow with `pairs` and Self-Referential Tables

This repository demonstrates a potential stack overflow error in Lua when using the `pairs` iterator with tables containing self-referential structures. The `bug.lua` file contains code that produces the infinite recursion. The `bugSolution.lua` demonstrates a solution using a different iteration method that avoids the problem.