# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
#Developed by: Sadhana R
#Register No.: 21225240129
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
#Developed by: Sadhana R
#Register No.: 212225240129
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
#Developed by: Sadhana R
#Register No.: 212225240129
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        
```



## Output:
<img width="1144" height="364" alt="Screenshot 2026-06-01 133354" src="https://github.com/user-attachments/assets/be5f0ce2-9a20-457d-9902-840895883d3e" />
<img width="1127" height="365" alt="image" src="https://github.com/user-attachments/assets/8e0d2999-d6ee-45ed-9f18-6fe0ca644056" />
<img width="1154" height="356" alt="image" src="https://github.com/user-attachments/assets/a6a3ce67-b775-420c-b74e-c8bfb29df7f8" />

## Result 
Thus the program executed successfully
