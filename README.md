# Find the maximum of a list of numbers

## REG-NO: 212223230071
## NAME: HARISH S
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
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large
```


iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
```




## Output:
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
