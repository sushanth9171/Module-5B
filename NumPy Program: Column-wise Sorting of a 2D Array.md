# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
~~~
import numpy as np
x=np.array(eval(input()))
sorted=np.sort(x,axis=0)
print("Given array ")
print("",x,"\n")
print(sorted)
~~~

## Output
<img width="973" height="600" alt="530303736-f2b8e1d2-1425-4246-a295-0b1d25359bc2" src="https://github.com/user-attachments/assets/815a3553-19f3-42a1-8944-becde9092473" />

## Result
Thus,the program has been executed successfully.

