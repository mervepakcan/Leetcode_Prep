# 010.  Container With Most Water (Medium)

## 📌 Problem
You are given an integer array height of length n. There are n vertical lines drawn such that the two endpoints of the ith line are (i, 0) and (i, height[i]).

Find two lines that together with the x-axis form a container, such that the container contains the most water.

Return the maximum amount of water a container can store.

Notice that you may not slant the container.


<img width="406" height="210" alt="photo" src="https://github.com/user-attachments/assets/9c9835c8-56b2-4575-960c-eb0f642f4b45" />

---

## 🔹 Example 1
**Input:**  
nums = [2,7,11,15], target = 9

**Output:**  
[0,1]

**Explanation:**  
Because `nums[0] + nums[1] == 9`, we return `[0, 1]`.

---

## 🔹 Example 2
**Input:**  
nums = [3,2,4], target = 6
**Output:**  
[0,1]

---

## Constraints
- 2 <= nums.length <= 10⁴  
- -10⁹ <= nums[i] <= 10⁹  
- -10⁹ <= target <= 10⁹  
- Only one valid answer exists.  

---

## Follow-up
Can you come up with an algorithm that is less than **O(n²)** time complexity?
