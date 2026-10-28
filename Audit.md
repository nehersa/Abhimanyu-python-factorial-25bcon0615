# Audit Report: Factorial Program

## 1. Program Details

* **File Name:** `factorial.py`
* **Language:** Python
* **Purpose:** Calculate the factorial of a number entered by the user.

## 2. Concepts Reviewed

* User input using `input()`.
* Type conversion using `int()`.
* Variables and assignment.
* `for` loop.
* Multiplication.
* Output using `print()`.

## 3. Code Review

The program initializes a variable `fact` to `1` and uses a `for` loop to multiply integers from `1` to the entered number. It then displays the calculated factorial.

## 4. Expected Behaviour

For example, the factorial of `5` is:

`5! = 5 × 4 × 3 × 2 × 1 = 120`

The program should calculate and display the factorial for valid non-negative integer input.

## 5. Limitations

* Negative input is not explicitly validated.
* Non-integer input may cause an error.
* Runtime testing has not been performed.

## 6. Recommendations

* Add input validation.
* Test with `0`, `1`, and positive integers.
* Verify the output for different inputs.

## 7. Audit Conclusion

The program demonstrates basic Python concepts, including loops, variables, user input, and arithmetic operations.

**Audit Status:** Code reviewed; runtime testing pending.
