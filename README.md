# PLP Python Week 6 - Safe Error Handling

Assignment practicing try/except for safe programs.

## Files
- **safe_tools.py** - Contains 3 safe functions: safe_divide, safe_number, and get_field that never crash.

## Why can the if check not catch abc on its own?
An if check cannot catch `int("abc")` because it causes a ValueError that crashes the program immediately. Only try/except can catch that runtime error and keep the program running.