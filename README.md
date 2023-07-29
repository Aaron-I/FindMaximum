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

i)	
# To find the maximum of marks using the list method sort.
# Developed by: AARON I
# RegisterNumber: 23002289
```
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max

```

ii)
# To find the maximum marks using the list method max().
# Developed by: AARON I
# RegisterNumber: 23002289
```
def max_marks(marks):
    maximum=max(marks)
    return maximum

```
iii) 
# To find the maximum marks without using builtin functions.
# Developed by: AARON I
# RegisterNumber: 23002289
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
       if i>max:
          max=i
    return max

```

## Output:
![output](/Screenshot%202023-07-26%20134402.png)
![output](/Screenshot%202023-07-26%20134524.png)
![output](/Screenshot%202023-07-26%20134944.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
