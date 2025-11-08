Given head, the head of a linked list, determine if the linked list has a cycle in it.

There is a cycle in a linked list if there is some node in the list that can be reached again by continuously following the next pointer. Internally, pos is used to denote the index of the node that tail's next pointer is connected to. Note that pos is not passed as a parameter.

Return true if there is a cycle in the linked list. Otherwise, return false.


<img width="317" height="146" alt="Screenshot 2025-11-08 at 20 08 18" src="https://github.com/user-attachments/assets/0086a8fd-37e4-4477-a5b3-66c58d0de5f0" />


Input: head = [3,2,0,-4], pos = 1

Output: true

Explanation: There is a cycle in the linked list, where the tail connects to the 1st node (0-indexed).


<img width="156" height="122" alt="Screenshot 2025-11-08 at 20 09 11" src="https://github.com/user-attachments/assets/a0c20e4b-e0ab-406c-b328-8434656b9f1b" />

Input: head = [1,2], pos = 0

Output: true

Explanation: There is a cycle in the linked list, where the tail connects to the 0th node.


<img width="89" height="90" alt="Screenshot 2025-11-08 at 20 09 48" src="https://github.com/user-attachments/assets/4fd41b8b-4468-4203-98d7-21da48b711e2" />


Input: head = [1], pos = -1

Output: false

Explanation: There is no cycle in the linked list.
 

Constraints:

The number of the nodes in the list is in the range [0, 104].
-105 <= Node.val <= 105
pos is -1 or a valid index in the linked-list.
 

Follow up: Can you solve it using O(1) (i.e. constant) memory?
