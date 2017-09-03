## Homework 3

You will need to solve the following tasks:

####  Create Intervals [(index.html)](./index.html)

From a Array of Integers you have to create a list of closed intervals as Arrays, so the intervals are covering all the values found in the set.

**Input:** Array of Integers.

**Output:** Array of Array of two Integers, indicating the endpoints of the interval. The Array should be sorted by start point of each interval.

**Example:**

```js
createIntervals([1, 2, 3, 4, 5, 7, 8, 12]) == [[1, 5], [7, 8], [12, 12]]
createIntervals([1, 2, 3, 6, 7, 8, 4, 5]) == [[1, 8]]
````

#### Count Inversion [(index2.html)](./index2.html)

You are given a sequence of unique numbers and you should count the number of inversions in this sequence.

Check out this example sequence: (1, 2, 5, 3, 4, 7, 6) and we can see here three inversions
- 5 and 3;
- 5 and 4;
- 7 and 6.

**Input:** A sequence as a tuple of integers.

**Output:** The inversion number as an integer.

```js
countInversion([1, 2, 5, 3, 4, 7, 6]) == 3
countInversion([0, 1, 2, 3]) == 0
```

Push your solutions into your own repository.