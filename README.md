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

def max_marks(marks):

    large=marks[len(marks)-1]

    marks.sort(reverse=True)

    large=marks[0]

    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):

    maxmark=0

    for i in marks:

        if i>maxmark:

            maxmark=i

    return maxmark

```



## Output:

![Screenshot 2024-04-15 204809](https://github.com/RITHISHlearn/FindMaximum/assets/145446645/38d5eeb4-f283-4efe-b865-45e2ea27890e)

![Screenshot 2024-04-15 204826](https://github.com/RITHISHlearn/FindMaximum/assets/145446645/e6bc2c08-210b-4976-a9fe-cc2de9addffb)

![Screenshot 2024-04-15 204838](https://github.com/RITHISHlearn/FindMaximum/assets/145446645/68c92185-6286-4cbd-abac-abea3e4024b5)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
