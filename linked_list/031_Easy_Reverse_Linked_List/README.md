Given the head of a singly linked list, reverse the list, and return the reversed list.

<img width="593" height="283" alt="Screenshot 2025-11-08 at 12 05 22" src="https://github.com/user-attachments/assets/94444a5e-a869-48ea-b045-b104f506d91c" />

Input: head = [1,2,3,4,5]

Output: [5,4,3,2,1]

<img width="468" height="566" alt="image" src="https://github.com/user-attachments/assets/b8c796f5-d07f-4413-9913-8412fde0837b" />

Input: head = [1,2]

Output: [2,1]

Example 3:

Input: head = []

Output: []
 

Constraints:

The number of nodes in the list is the range [0, 5000].
-5000 <= Node.val <= 5000
 

Follow up: A linked list can be reversed either iteratively or recursively. Could you implement both?


**Solution:**

**Iterative Solution:**
The iterative approach uses two pointers, prev and curr, to reverse the links one by one. At each step, we store the next node, make the current node point to the previous one, then move both pointers forward. This process continues until all links are reversed, and prev becomes the new head of the list.

<img width="1446" height="657" alt="Screenshot 2025-11-08 at 13 54 43" src="https://github.com/user-attachments/assets/ea887bfa-f563-4598-864e-a3f62d97f4b7" />


**Recursive Solution:**
The recursive approach goes all the way to the end of the list and reverses the connections while returning. Each recursive call processes the rest of the list first, then flips the link between the current node and its next node. When the function unwinds, all links have been reversed, and the last node becomes the new head.


<img width="1324" height="616" alt="Screenshot 2025-11-08 at 13 11 46" src="https://github.com/user-attachments/assets/67be113e-ba4d-4e7e-ad4d-3e7b9e879ced" />
