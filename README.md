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
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(a):
    large=max(a)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list):
    a=0
    for i in list:
        if i>a:
            a=i
    return a
    


```



## Output:

![Screenshot (215)](https://github.com/RahiniAchudhan/FindMaximum/assets/145742838/db0878b2-7357-4afb-877c-077bfe8438bf)

![Screenshot (216)](https://github.com/RahiniAchudhan/FindMaximum/assets/145742838/1e37feb6-4bf0-4961-8343-0a5f4375e0e3)

![Screenshot (217)](https://github.com/RahiniAchudhan/FindMaximum/assets/145742838/eddbd332-6d01-4933-af51-2847f7d9027c)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
