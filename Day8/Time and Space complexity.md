**Time and Space complexity:**



you are searching a contact

\-- Instead of searching one by one searching the contact directly



**Time complexity --** How fast the code runs whenever the input grows 0(n)



**Definition:**

&#x20;How the running time increases whenever the input size increases.



if n=5 -- code will run 5 times

&#x20;  n=100 -- code will run 100 times



\-- o(n) -- **Linear time complexity**



array = \[1, 2, 3, 4,5]

for i in array:

&#x20;     print(i)

&#x20;

2\. O(n^2) --  **Quadratic**

&#x20;









3\. O(1) **Constant time**

&#x20;   no matter the input, runs only once

&#x20;  array = \[1, 2, 3, 4, 5]

&#x20;  array\[3]



4\. **Total time complexity:**

&#x20;     O(1)    --- **Accessing elements**

&#x20;     O(LOGN) --- **Binary search**

&#x20;     O(N)     --- **Linear search**

&#x20;     O(N LOG N)--- **merge and quick**

&#x20;     O(N^2)  --- **selectin sort**

&#x20;     O(2^N) -- **Recursions (Factorial)**

&#x20;     O(N!) --- **Traveling sales man problem**



&#x20;5. **Space complexity:**

&#x20;    --  Memory allocation

&#x20;     Ex: a = 10

&#x20;         b = 10

&#x09;  for i in range(array):

&#x09;	total += 1



**Prefix Sum:**

&#x20; **Prefix Sum Array :** Prefix sum array scores the cumulative sum of elements up to each index.

array=\[1,2,3,4,5]

prefix=\[1,3,6,10,15]

**Ex:**

&#x20;	array=\[2,4,6,8,10]

&#x09;prefix=\[2,6,12,20,30]

**Formula:**

&#x09;prefix\[1] = prefix\[I-1] + array\[I]

&#x09;array=\[1,2,3,4]



prefix=\[0]\*len(arr)

