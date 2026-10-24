FIBONACCI SERIES IN PYTHON

1. Aim:
   To write a Python program to print the Fibonacci series.

2. Description:
   The Fibonacci series is a sequence in which each number is the sum of the previous two numbers. The series starts with 0 and 1.

3. Requirements:

* Python 3
* Any Python IDE or editor

4. Program:
   n = int(input("Enter the number of terms: "))

a, b = 0, 1

for i in range(n):
print(a, end=" ")
a, b = b, a + b

5. Sample Output:
   Enter the number of terms: 10
   0 1 1 2 3 5 8 13 21 34

6. Conclusion:
   The program successfully generates the Fibonacci series for the specified number of terms.
