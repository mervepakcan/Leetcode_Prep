# 017. Word Search (Medium)

## 📌 Problem
Given an m x n grid of characters board and a string word, return true if word exists in the grid.

The word can be constructed from letters of sequentially adjacent cells, where adjacent cells are horizontally or vertically neighboring. The same letter cell may not be used more than once.  

---

## 🔹 Example 1
<img width="638" height="476" alt="image" src="https://github.com/user-attachments/assets/5304ff1b-f004-4eec-a7d8-9f18683e203f" />

**Input:**  
board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "ABCCED"

**Output:**  
true

---

## 🔹 Example 2
<img width="640" height="476" alt="image" src="https://github.com/user-attachments/assets/e8329806-f4aa-41b2-9f46-503b710ec5cd" />

**Input:**  
board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "SEE"
**Output:**  
true

---

## 🔹 Example 3
<img width="634" height="478" alt="image" src="https://github.com/user-attachments/assets/43c6dbc8-9238-4c14-9950-e9c11caf95f7" />

**Input:**  
board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "ABCB"
**Output:**  
false

--- 


## Constraints
- m == board.length
- n = board[i].length
- 1 <= m, n <= 6
- 1 <= word.length <= 15
- board and word consists of only lowercase and uppercase English letters.

---

## Follow-up
Could you use search pruning to make your solution faster with a larger board?
