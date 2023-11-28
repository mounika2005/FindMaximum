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
Developed by: lakshmi mounika
RegisterNumber: 23004124
'''
def max_marks(marks):
    a=sorted(marks)
    b=a[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: lakshmi mounika
RegisterNumber: 23004124
'''
def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: lakshmi mounika
RegisterNumber: 23004124
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```

## Output:
![Screenshot 2023-11-28 223528](https://github.com/mounika2005/FindMaximum/assets/145633112/bf505ee2-f64c-40f4-9ef1-f14ef8e94061)
![Screenshot 2023-11-28 223545](https://github.com/mounika2005/FindMaximum/assets/145633112/5b3465ee-f192-4867-a0a8-610f1302ae04)
![Screenshot 2023-11-28 223555](https://github.com/mounika2005/FindMaximum/assets/145633112/9fde0e2c-bfba-41e0-913c-8eff56d8d85e)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
