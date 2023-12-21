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
``` Python
Program to mark the maximum of marks using the list method sort
Developed by: ARAVIND R
RegisterNumber: 23005370
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by: ARAVIND R
RegisterNumber: 2305370
def max_marks(marks):
    max1=max(marks)
    return max1

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: ARAVIND R
RegisterNumber: 23005370
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
![Screenshot 2023-12-21 220350](https://github.com/ARAVIND23005370/FindMaximum/assets/148514836/23176ab9-0338-4df4-8e7e-bcf853f7e024)
![Screenshot 2023-12-21 220358](https://github.com/ARAVIND23005370/FindMaximum/assets/148514836/c9156bcc-2510-438d-943e-cbdfd5d0f949)
![Screenshot 2023-12-21 220405](https://github.com/ARAVIND23005370/FindMaximum/assets/148514836/016d2480-97de-43b9-827a-e1fe99a6a6ef)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
