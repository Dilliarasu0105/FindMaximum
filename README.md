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
'''Program to find the maximum of marks using the list method sort
Developed by: DILLIARASU M
Register No : 212223230049'''

def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
'''Program to find the maximum marks using the list method max().
Developed by: DILLIARASU M
Register No : 212223230049'''

def max_marks(array):
    return max(array)
```

iii) # To find the maximum marks without using builtin functions.
```Python
'''Program to find the maximum marks without using builtin functions.
Developed by: DILLIARASU M
Register no : 212223230049'''

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```

## Output:
i]# To find the maximum of marks using the list method sort.
![Screenshot 2024-04-14 121148](https://github.com/Dilliarasu0105/FindMaximum/assets/144979593/55e2fe55-1d86-4767-93b5-e0f4687c693d)

ii]# To find the maximum marks using the list method max().
![Screenshot 2024-04-14 121209](https://github.com/Dilliarasu0105/FindMaximum/assets/144979593/ea826489-c5a4-497c-ade4-5a8f62d681bd)

iii]# To find the maximum marks without using builtin functions.
![Screenshot 2024-04-14 121241](https://github.com/Dilliarasu0105/FindMaximum/assets/144979593/4e9c3b99-851f-43a9-a9b6-ab769c872ea4)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
