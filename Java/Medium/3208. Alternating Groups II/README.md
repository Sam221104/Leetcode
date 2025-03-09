## 3208. Alternating Groups II

There is a circle of red and blue tiles. You are given an array of integers colors and an integer k. The color of tile i is represented by colors[i]:

colors[i] == 0 means that tile i is red.
colors[i] == 1 means that tile i is blue.
An alternating group is every k contiguous tiles in the circle with alternating colors (each tile in the group except the first and last one has a different color from its left and right tiles).

Return the number of alternating groups.

Note that since colors represents a circle, the first and the last tiles are considered to be next to each other.

 

Example 1:

Input: colors = [0,1,0,1,0], k = 3

Output: 3

Explanation:
![image](https://github.com/user-attachments/assets/7c5d78f4-5a0d-4e0e-8c4b-e3ea8bd3d381)



Alternating groups:


![image](https://github.com/user-attachments/assets/a7479c03-73e0-4dd0-89cb-b3ee7650d65a)
![image](https://github.com/user-attachments/assets/ee8f565a-9897-4fee-9e71-927ab049c48f)
![image](https://github.com/user-attachments/assets/f8f8ebfc-f5b1-443a-a1d1-74e6c4ce8586)


Example 2:

Input: colors = [0,1,0,0,1,0,1], k = 6

Output: 2

Explanation:
![image](https://github.com/user-attachments/assets/2d6f84f5-978b-4fb4-9d6f-167818e639e8)



Alternating groups:
![image](https://github.com/user-attachments/assets/5ced56d5-99d6-4623-953b-2b43ea7fa7c2)
![image](https://github.com/user-attachments/assets/570130e9-1f44-40e6-ac5d-b0b7833e745f)



Example 3:

Input: colors = [1,1,0,1], k = 4

Output: 0

Explanation:
![image](https://github.com/user-attachments/assets/605d74a3-8359-4d17-b0c5-9fcb03c89f35)



 

Constraints:

3 <= colors.length <= 105
0 <= colors[i] <= 1
3 <= k <= colors.length
