Given the roots of two binary trees p and q, return true if the trees are equivalent, otherwise return false.

Two binary trees are considered equivalent if they share the exact same structure and the nodes have the same values.



<img width="488" height="186" alt="Screenshot 2025-11-09 at 21 02 41" src="https://github.com/user-attachments/assets/96d452cd-d4cb-4683-a041-282bec7f43f1" />


Input: p = [1,2,3], q = [1,2,3]

Output: true

<img width="399" height="235" alt="Screenshot 2025-11-09 at 21 02 49" src="https://github.com/user-attachments/assets/d8ade608-7f52-459e-bcff-311a83af159f" />


Input: p = [1,2], q = [1,null,2]

Output: false

<img width="493" height="191" alt="Screenshot 2025-11-09 at 21 02 59" src="https://github.com/user-attachments/assets/5960b609-ba89-4472-9a69-3ccde66f042d" />

Input: p = [1,2,1], q = [1,1,2]

Output: false

Constraints:

The number of nodes in both trees is in the range [0, 100].
-104 <= Node.val <= 104
