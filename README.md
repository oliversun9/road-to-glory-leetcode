# road-to-glory-leetcode
My journey of LeetCoding.\
I borrowed the phrase Road to Glory from FIFA, where it refers to building an awesome team through many hours of grinding.\
I did 35 questions before creating this repo, and now I'm aiming to do 5 questions (2 easy + 3 medium) per day.

Questions I did:
* P17. Letter Combinations of a Phone Number - I solved it by representing an n-dimensional array with a 1D vector, but I saw a much superior method using queue/BFS. July 26, 21
* P20. Valid Parentheses - Just thought I should do a string question. I used stack, but I saw a very interesting solution that calls replace on paretheses repeatedly. July 25, 21
* P31. Next Permutation - A fun question but not too hard (it's medium after all). The question kind of gave away its solution when it says if there is no bigger permutation, revert it. It happened to be the same as the top voted solution. I also saw a very cool solution that uses a tree. I implemented my own reverse function because I sort of forgot I could use reverse from the standard library. July 26, 21
* P62. Unique Paths - I used dp with 2D array but it can be improved using only one array/vector.  July 25, 21
* P63. Unique Paths II - I modified the given matrix but I probably shouldn't have. July 25, 21
* P64. Minimum Path Sum - My DP problem of the day, but unfortunately greedy doesn't solve it. July 26, 21
* P91. Decode Ways - Essentially fibonacci number with checks. July 27, 21
* P111. Minimum Depth of Binary Tree - I used recursion (DFS), and also BFS to see if it's faster. My BFS solution was only slightly faster than my recursion solution. (220ms and 224ms) July 25, 21
* P112. Path Sum - I used recursion but I could have used stack/queue and pushed node with modified values (node->value + parent->value). July 26, 21
* P114. Flatten Binary Tree to Linked List - I used recursion but I saw a better solution using iteration that always go to the right most leaf of the left child. July 25, 21
* P116. Populating Next Right Pointers in Each Node - I did it with DFS recursion at first, but it was not fast enough. Then I used queue/BFS, still not faster. Then I traversed the tree in constant space taking advantage of 'next', and it's finally faster. - July 27, 21
* P117. Populating Next Right Pointers in Each Node II - I did it with constant space using next, but each node is visited quite a few times (3 I think?). A mucher better and cleaner approach is to loop on the higher level instead fo the lower level. - July 27, 21
* P118. Pascal's Triangle - I did it by inserting an element one by one for each row. A better solution I saw modified a copy of the last row, adding the last two entries and starting from the last element to avoid inserting 1 at the beginning. - July 27, 21
* P136. Single Number - Initially, I didn't know it's bit manipulation and had a hard time figuring out a solution of linear time and constant space. It never occurred to me XOR is commutative haha. 
* P226. Invert Binary Tree - I used recursion at first then redid the problem with queue/BFS. July 26, 2021
