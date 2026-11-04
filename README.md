# Week 6 Assignment: Error Handling & Debugging

## Files Included
- **safe_tools.py** — Contains robust Python functions using `try / except` blocks to safely handle division by zero errors, invalid number conversions, and missing dictionary keys without crashing the program.

## Assignment Question & Explanation
**Why can the `if` check not catch `"abc"` on its own?**

An `if` check cannot easily anticipate every malformed data type or unexpected user input format beforehand. A `try / except` block is designed to safely attempt an operation and catch the runtime exception when Python encounters unexpected input like `"abc"`.