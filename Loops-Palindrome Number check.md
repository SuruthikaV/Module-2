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
```
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)
def combination(n, k):
    return factorial(n) // (factorial(k) * factorial(n - k))
num_rows = int(input("Enter number of rows: "))
for i in range(num_rows):
    print(' ' * (num_rows - i - 1), end='')
    for j in range(i + 1):
        print(combination(i, j), end=' ')
    print()

```
## Output
<img width="201" height="225" alt="image" src="https://github.com/user-attachments/assets/4d151a94-914c-4bbc-bf28-f78ae8234539" />

## Result
Thus, the program has been successfully executed
