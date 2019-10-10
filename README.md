# Challenge Problem Answers

## Challenge 1
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
