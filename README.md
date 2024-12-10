# Go: Unhandled Nil Map Panic

This repository demonstrates a common error in Go: accessing a map without checking if it's nil.  Attempting to access a nil map results in a runtime panic.

The `bug.go` file shows the problematic code.  The `bugSolution.go` provides a corrected version with proper nil checks.

This example highlights the importance of defensive programming when working with maps in Go.