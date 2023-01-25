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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)

![maxmarkssortpy](https://user-images.githubusercontent.com/120623583/214623582-f9741021-be4d-4aa4-bbc9-3a50d3862530.png)

ii)

![maxmarkslistpyt](https://user-images.githubusercontent.com/120623583/214623728-b4380657-1c31-45b4-8e0f-94ecd1a7de82.png)

iii)

![maxmarksbuiltinpy](https://user-images.githubusercontent.com/120623583/214623863-4da18add-57db-46c1-889d-8aff1d13edac.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
