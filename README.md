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
```
#a program to mark the maximum of marks using the list method sort.
#DEVELOPED BY: ARJUN N S
#REGISTER NUMBER: 212223230020
def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
```
#a program to find the maximum marks using the list method max().
#DEVELOPED BY: ARJUN N S
#REGISTER NUMBER: 212223230020

def max_marks(array):
    return max(array)


```

iii) # To find the maximum marks without using builtin functions.
```
#a program to find the maximum marks without using builtin functions.
#DEVELOPED BY: ARJUN N S
#REGISTER NUMBER: 212223230020

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```



## Output:

i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/NSArjun/FindMaximum/assets/148233801/16495c6c-7faf-4938-8f3c-8a1eb4b9c512)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/NSArjun/FindMaximum/assets/148233801/a0474dfa-ad06-4a1d-b1db-e1832eaaaaaa)




iii) # To find the maximum marks without using builtin functions.

![image](https://github.com/NSArjun/FindMaximum/assets/148233801/30b9227e-fd31-4822-a644-a2d10d67177c)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
