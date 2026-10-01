# HackerRank 3rd Semester Algorithm Portfolio

## Student Information

| Details | Information |
|---|---|
| **Name** | Preetham Gowda JS |
| **USN / Student ID** | R25EF200 |
| **Semester** | 3rd Semester |
| **Branch** | Computer Science and Engineering |
| **Language Used** | Java |

## Profiles

- **HackerRank:** https://www.hackerrank.com/profile/preethamgowdasa1
- **GitHub Repository:** https://github.com/PreethamGowdaJS/HackerRank-3rdSem-Algorithm-Portfolio.git

---

## About This Portfolio

This repository contains my solutions for five mandatory algorithmic problems completed as part of my 3rd Semester CSE coursework.

The portfolio focuses on fundamental programming and algorithmic techniques including arrays, counting, insertion sort, binary search, greedy algorithms, and sorting.

Each solution is implemented in Java with an appropriate algorithm and includes time and auxiliary space complexity analysis. Evidence of completed HackerRank submissions and badge achievements, where applicable, is also maintained as part of the portfolio.

---

## Completed Problems

| No. | Problem | Main Technique | Time Complexity | Auxiliary Space |
|---|---|---|---|---|
| 1 | Mini-Max Sum | Array traversal | O(N) | O(1) |
| 2 | Birthday Cake Candles | Counting / Array traversal | O(N) | O(1) |
| 3 | Insertion Sort – Part 1 | Insertion Sort | O(N) | O(1) |
| 4 | Binary Search | Divide and Conquer | O(log N) | O(1) |
| 5 | Mark and Toys | Greedy + Sorting | O(N log N) | O(N)* |

\* The additional memory used by sorting depends on the Java sorting implementation.

---

# 1. Mini-Max Sum

### Problem

Given five positive integers, calculate the minimum and maximum values that can be obtained by summing exactly four of the five integers.

### Approach

- Calculate the total sum of all elements.
- Find the minimum element.
- Find the maximum element.
- Minimum sum = total sum − maximum element.
- Maximum sum = total sum − minimum element.

This approach avoids sorting the array and calculates the result using a single traversal.

### Complexity

- **Time:** O(N)
- **Auxiliary Space:** O(1)

### Evidence

Accepted HackerRank submission evidence is included in the portfolio.

---

# 2. Birthday Cake Candles

### Problem

Given the heights of candles, determine how many candles have the maximum height.

### Approach

- Traverse the array once.
- Keep track of the current maximum candle height.
- Whenever a new maximum is found, reset the count to 1.
- If another candle has the same maximum height, increment the count.
- Return the final count.

### Complexity

- **Time:** O(N)
- **Auxiliary Space:** O(1)

### Evidence

Accepted HackerRank submission evidence is included in the portfolio.

---

# 3. Insertion Sort – Part 1

### Problem

Insert the last element of an array into its correct position in the already sorted portion of the array while displaying the intermediate steps.

### Approach

- Store the last element as the value to insert.
- Start comparing it with the elements before it.
- Shift larger elements one position to the right.
- Display the array after every required shift.
- Insert the stored value into its correct position.
- Display the final array.

### Complexity

- **Time:** O(N) worst case
- **Auxiliary Space:** O(1)

### Evidence

Accepted HackerRank submission evidence is included in the portfolio.

---

# 4. Binary Search

### Problem

Find the position of a given value in a sorted array using binary search.

### Approach

- Set two pointers: `left` and `right`.
- Calculate the middle index.
- If the middle element equals the target, return its index.
- If the middle element is smaller than the target, search the right half.
- Otherwise, search the left half.
- Continue until the target is found.

Binary search repeatedly divides the search space into approximately two halves.

### Complexity

- **Time:** O(log N)
- **Auxiliary Space:** O(1)

### Evidence

Accepted HackerRank submission evidence is included in the portfolio.

---

# 5. Mark and Toys

### Problem

Given the prices of toys and a fixed budget, determine the maximum number of toys that can be purchased.

### Approach

- Sort the toy prices in ascending order.
- Start purchasing from the cheapest toy.
- Add each price while the total remains within the budget.
- Stop when the next toy cannot be purchased.
- The number of purchased toys is the answer.

The greedy strategy works because purchasing cheaper toys first allows the maximum number of toys to be purchased within the given budget.

### Complexity

- **Time:** O(N log N)
- **Auxiliary Space:** O(N)*

\* The additional memory used by sorting depends on the Java sorting implementation.

### Evidence

Accepted HackerRank submission evidence is included in the portfolio.

---

# HackerRank Badge Evidence

## Badge Status

My HackerRank profile is included above as evidence of participation and completed challenges.

**HackerRank Profile:**

https://www.hackerrank.com/profile/preethamgowdasa1

### Badge Evidence

Evidence of any HackerRank badges earned will be included in the portfolio.

If the required 3-Star milestone is achieved, the corresponding badge evidence will also be included.

---

# Accepted Submission Evidence

Evidence of successful HackerRank submissions for all five completed problems is included with the portfolio.

The evidence demonstrates that the solutions were submitted successfully and accepted by HackerRank.

---

# Repository Structure

```text
HackerRank-3rdSem-Algorithm-Portfolio/
│
├── README.md
│
├── Evidence/
│
├── 01-Mini-Max-Sum/
│   └── Solution.java
│
├── 02-Birthday-Cake-Candles/
│   └── Solution.java
│
├── 03-Insertion-Sort-Part-1/
│   └── Solution.java
│
├── 04-Binary-Search/
│   └── Solution.java
│
└── 05-Mark-and-Toys/
    └── Solution.java
```

---

# Learning Outcomes

Through these problems, I practiced:

- Array traversal and processing
- Finding minimum and maximum values
- Counting occurrences
- Simulation of insertion sort
- Divide-and-conquer searching
- Greedy problem solving
- Sorting and optimization
- Time and auxiliary space complexity analysis
- Writing and testing Java solutions
- Using HackerRank for algorithmic practice
- Maintaining algorithm solutions using Git and GitHub

---

# Conclusion

This portfolio demonstrates my understanding of fundamental algorithms and their efficiency. The selected problems helped me practice different approaches to solving programming problems while considering time and auxiliary space complexity.

The solutions were implemented in Java and submitted through HackerRank. The corresponding source files, submission evidence, and documentation are maintained in this GitHub repository for reference and evaluation.

---

## Student

**Preetham Gowda JS**  
**SRN:** R25EF200  
**3rd Semester – Computer Science and Engineering**  
**REVA University**