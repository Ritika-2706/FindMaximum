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
max_marks([0,60,80,30,76,23])


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(list1):
    maxi = list1[0]
    for i in list1:
        if i>maxi:
            maxi=i
    return maxi


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    maxi=max(marks)
    return maxi


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://user-images.githubusercontent.com/93427238/154844215-738a89a6-f8d9-45a6-a3d9-13d7e7e33d03.png)
![image](https://user-images.githubusercontent.com/93427238/154844281-d0c7ae94-4ce9-4471-a792-70e5e1804bb5.png)
![image](https://user-images.githubusercontent.com/93427238/154844291-94fbb2a0-9a71-4490-95c8-05cd1fad384f.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
