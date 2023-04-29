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
Developed by: G.Chethan kumar.
RegisterNumber: 212222240022.
'''
def max_marks(marks):
    marks.sort()
    return (marks[-1])
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: G.Chethan kumar.
RegisterNumber: 212222240022.
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: G.Chethan kumar.
RegisterNumber: 212222240022.
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)
![Screenshot 2023-04-29 131257](https://user-images.githubusercontent.com/118348224/235291326-4e6f0ca8-0ac2-4132-8509-fd99087f0223.png)

ii)
![Screenshot 2023-04-29 131641](https://user-images.githubusercontent.com/118348224/235291387-ef729f90-5265-41d9-a055-0451fc5d9772.png)

iii)
![Screenshot 2023-04-29 131657](https://user-images.githubusercontent.com/118348224/235291391-4fe31b59-c8f1-494a-8a49-9e116aca2def.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
