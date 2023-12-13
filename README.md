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
Developed by: SANJAY C
RegisterNumber: 23013498
'''
def max_marks(marks):
    l=marks
    l.sort()
    return max(marks)

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:SANJAY C 
RegisterNumber: 23013498
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: SANJAY C
RegisterNumber: 23013498 
'''
def max_marks(list1):
    maxnum=0
    for i in list1:
        if maxnum<i:
            maxnum=i
    return maxnum        
            


```
## Output:
i)![](./1.png)
ii)![](./2.png)
iii)![](./3.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.