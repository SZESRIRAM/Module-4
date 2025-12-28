# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
story.txt
```
The sun rises in the east.
There was a small village near the river.
Trees were tall and green.
Time waits for no one.
Once upon a time, there lived a king.
```
program
```
file = open(r"C:\Users\acer\Documents\Python\story.txt", "r")
count = 0
for line in file:
    if not line.startswith("T"):
        count += 1
print(count)
file.close()
```

## Output
<img width="294" height="47" alt="image" src="https://github.com/user-attachments/assets/51c49648-0b27-4481-a9bd-84475ce1542f" />


## Result
Thus, the given program has been executed successfully and the number of lines not starting with the letter 'T' is counted correctly.
