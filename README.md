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
'''
Program to mark the maximum of marks using the list method sort
Developed by:Ezhil sree J
RegisterNumber:23012968
'''
def max_marks(marks):
    sm=sorted(marks,reverse=True)
    max=sm[0]
    return max
marks=list(input())
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Ezhil sree J 
RegisterNumber:23012968
'''
def max_marks(marks):
    sm=max(marks)
    return sm
marks=list(input())

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Ezhil sree J
RegisterNumber:23012968
'''
def max_marks(list1):
    maximum=0
    for i in list1:
        if (i>maximum):
            maximum=i
    return maximum
```

## Output:
![image](https://github.com/EzhilsreeJ/FindMaximum/assets/144870412/ead3ffc7-e246-4401-96cd-8730728b1cfd)
![image](https://github.com/EzhilsreeJ/FindMaximum/assets/144870412/f4e8b2e2-f30d-4328-b520-16c0e6889d86)
![image](https://github.com/EzhilsreeJ/FindMaximum/assets/144870412/2c9ba826-b219-426b-ac48-7732fa164f1f)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
