# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
~~~
import numpy as np
x=np.array(eval(input()))
y=np.array(eval(input()))
print(np.where(x>y))
print(np.where(x==y))
~~~


## Output
<img width="1142" height="262" alt="530304326-17eae0ca-3f6f-4b9a-8225-d16756677458" src="https://github.com/user-attachments/assets/2e9a0ce8-f236-47cb-a93e-edae3232dc91" />

## Result
Thus,the program has been executed successfully.

