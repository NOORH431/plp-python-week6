# Week 6 Assignment – Safe Functions

- `safe_tools.py` — Defines and tests `safe_divide`, `safe_number`, and `get_field` using `try` / `except`.
- `README.md` — Describes the assignment files and explains the input-validation question.

An `if` check can test a condition before conversion, but it cannot reliably determine whether every possible text value is a valid integer. Calling `int()` is what attempts the conversion, and invalid text such as `"abc"` raises a `ValueError`, which the `except` block catches.
