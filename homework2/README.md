## Homework 2

You will need to solve the following tasks:

####  Median [(index.html)](./index.html)

Find the median in the given array.

**Input:** An array as a list of integers.

**Output:** The median as a float or an integer.

**Example:**

```js
median([1, 2, 3, 4, 5]) == 3
median([3, 1, 2, 5, 3]) == 3
median([1, 300, 2, 200, 1]) == 2
median([3, 6, 20, 99, 10, 15]) == 12.5
````

#### Absolute Sorting [(index2.html)](./index2.html)

Let's try some sorting. Here is an array with the specific rules.

The array has various numbers. You should sort it, but sort it by absolute value in ascending order. For example, the sequence (-20, -5, 10, 15) will be sorted like so: (-5, 10, 15, -20). Your function should return the sorted list .

**Input:** An array of numbers.

**Output:** The list or tuple (but not a generator) sorted by absolute values in ascending order.

```js
absoluteSorting((-20, -5, 10, 15)) == [-5, 10, 15, -20] # or (-5, 10, 15, -20)
absoluteSorting((1, 2, 3, 0)) == [0, 1, 2, 3]
absoluteSorting((-1, -2, -3, 0)) == [0, -1, -2, -3]
```


Push your solutions into your own repository.