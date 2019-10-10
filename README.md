# Challenge Problem Answers

If you want to use this solution, you must give me a step-by-step explanation on how the code works. Without it, this will not count.

## Challenge 1 - Even Fibonacci Numbers
```
counter = 2
oldNumber = 1
middleNumber = 1
newNumber = 2
while newNumber < 4000000:
  middleNumber = newNumber
  newNumber = newNumber + oldNumber 
  if (newNumber % 2 == 0):
    counter = counter + newNumber
  oldNumber = middleNumber
print(counter)

```
