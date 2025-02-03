# Unexpected Immutable Behavior in Ruby Class

This repository demonstrates a common, yet subtle, error in Ruby that can lead to unexpected behavior. It showcases a class with a getter method (`value`) for an instance variable but lacks a corresponding setter method.  This can lead developers to believe the attribute is mutable when it is actually effectively immutable.

The `bug.rb` file shows the erroneous code, and `bugSolution.rb` provides the corrected implementation.

## How to reproduce

1. Clone this repository.
2. Run `ruby bug.rb`