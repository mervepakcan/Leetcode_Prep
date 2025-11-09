Given the roots of two binary trees root and subRoot, return true if there is a subtree of root with the same structure and node values of subRoot and false otherwise.

A subtree of a binary tree tree is a tree that consists of a node in tree and all of this node's descendants. The tree tree could also be considered as a subtree of itself.

 <img width="493" height="410" alt="Screenshot 2025-11-09 at 23 38 04" src="https://github.com/user-attachments/assets/006e0c1f-9f85-4f57-b597-6241937dcb2d" />


Example 1:


Input: root = [3,4,5,1,2], subRoot = [4,1,2]

Output: true

<img width="487" height="479" alt="Screenshot 2025-11-09 at 23 38 16" src="https://github.com/user-attachments/assets/be778829-d006-4474-908f-7c8d0436cee7" />

Example 2:

Input: root = [3,4,5,1,2,null,null,null,null,0], subRoot = [4,1,2]

Output: false

 

Constraints:

The number of nodes in the root tree is in the range [1, 2000].
The number of nodes in the subRoot tree is in the range [1, 1000].
-104 <= root.val <= 104
-104 <= subRoot.val <= 104
