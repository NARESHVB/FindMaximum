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
Developed by:NARESH.V 
RegisterNumber:212222110027
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:NARESH.V 
RegisterNumber:212222110027 
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max



```
## Sample Input and Output
![output](./img/max_marks1.jpg)
![image](https://github.com/NARESHVB/FindMaximum/assets/119393642/5f3e00e7-6836-419b-b7e0-38e8da082da5)
![image](https://github.com/NARESHVB/FindMaximum/assets/119393642/3b3f55b6-7966-4b2c-9aa2-bb9775f3d31b)
![image](https://github.com/NARESHVB/FindMaximum/assets/119393642/8baae283-f4f1-4901-b19f-17b893a71639)


## Output:
![image](https://github.com/NARESHVB/FindMaximum/assets/119393642/5d03d599-2de8-4ff3-a8fe-f709d778f84c)
![image](https://github.com/NARESHVB/FindMaximum/assets/119393642/4c2c2e95-392d-405d-9cfc-a386323606a2)
![image](https://github.com/NARESHVB/FindMaximum/assets/119393642/b6ed106d-a8fe-48ac-8266-9c9f20bbb3d6)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
