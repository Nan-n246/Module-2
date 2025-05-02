## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
![Screenshot 2025-05-02 104819](https://github.com/user-attachments/assets/af032dbf-bcc5-4925-bd0a-a4867d5c31e3)

## Output

![Screenshot 2025-05-02 104909](https://github.com/user-attachments/assets/10a654d1-c088-4afe-aa12-8688d7632e15)

## Result
Thus, the program has been successfully executed.
