# road-to-glory-leetcode
My journey of LeetCoding. July 25 - present \
I borrowed the phrase Road to Glory from FIFA, where it refers to building an awesome team through many hours of grinding.\
I did around 30 questions before creating this repo, and now I'm aiming to do 5 questions per day.

Questions I did:
* P15. 3Sum. Sort and two-sum n times. Aug 9, 21
* P17. Letter Combinations of a Phone Number - I solved it by representing an n-dimensional array with a 1D vector, but I saw a much superior method using queue/BFS. July 26, 21
* P19. Remove Nth Node From End of List. Deja vu. Aug 9, 21
* P20. Valid Parentheses - Just thought I should do a string question. I used stack, but I saw a very interesting solution that calls replace on paretheses repeatedly. July 25, 21
* P21. Merge Two Sorted Lists.  Aug 10, 21
* P23. Merge k Sorted Lists. Make heap in place, also used a dummy head. Aug 6, 21
* P31. Next Permutation - A fun question but not too hard (it's medium after all). The question kind of gave away its solution when it says if there is no bigger permutation, revert it. It happened to be the same as the top voted solution. I also saw a very cool solution that uses a tree. I implemented my own reverse function because I sort of forgot I could use reverse from the standard library. July 26, 21
* P33. Search in Rotated Sorted Array - I solved using binary search, but my favorite solution from discussions uses infinity to represent the value in the middle. the top voted solution using read mid is also nice. - July 28, 21
* P34. Find First and Last Position of Element in Sorted Array  - July 28, 21
* P46. Permutations - I did it using a method unrelated to backtracking, because I'm not familiar with backtracking. This the second time I heard of back tracking, and I saw some good backtracking solutions. It looks like DFS. I need to get more used to backtracking. - July 28, 21
* P54. Spiral Matrix. Straightforward question but my solution is not elegant at all. A better solution that I read updates a boundary after traversing a row or column. A very smart python solution prints top row and rotate the matrix! Aug 9, 21
* P56. Merge Intervals - I sorted and then merge, which is also the top voted answer. July 29, 21
* P62. Unique Paths - I used dp with 2D array but it can be improved using only one array/vector.  July 25, 21
* P63. Unique Paths II - I modified the given matrix but I probably shouldn't have. July 25, 21
* P64. Minimum Path Sum - My DP problem of the day, but unfortunately greedy doesn't solve it. July 26, 21
* P66. Plus One. A smarter solution only adds 0 at the end when necessary.  Aug 10, 21
* P73. Set Matrix Zeroes. The constant space solution not too hard to come up with, but took me a little while, probably more than ten minutes. I should've done it faster. Aug 6, 21
* P74. Search a 2D Matrix. Aug 11, 21
* P75. Sort Colors - I used the four-subarrays method. July 29, 21
* P91. Decode Ways - Essentially fibonacci number with checks. July 27, 21
* P105. Construct Binary Tree from Preorder and Inorder Traversal. I did it the straightforward way (so sad), splitting the inorder array. A much superior solution keeps track of the stopping value and runs in constant space. The solutio using stack is also smart. Aug 11, 21
* P106. Construct Binary Tree from Inorder and Postorder Traversal - My solution perfomed a search in each iteration but then i learned from other solutions that store the results in a map is a better idea. - July 29, 21
* P108. Convert Sorted Array to Binary Search Tree - not difficult. July 28, 21
* P111. Minimum Depth of Binary Tree - I used recursion (DFS), and also BFS to see if it's faster. My BFS solution was only slightly faster than my recursion solution. (220ms and 224ms) July 25, 21
* P112. Path Sum - I used recursion but I could have used stack/queue and pushed node with modified values (node->value + parent->value). July 26, 21
* P114. Flatten Binary Tree to Linked List - I used recursion but I saw a better solution using iteration that always go to the right most leaf of the left child. July 25, 21
* P116. Populating Next Right Pointers in Each Node - I did it with DFS recursion at first, but it was not fast enough. Then I used queue/BFS, still not faster. Then I traversed the tree in constant space taking advantage of 'next', and it's finally faster. - July 27, 21
* P117. Populating Next Right Pointers in Each Node II - I did it with constant space using next, but each node is visited quite a few times (3 I think?). A mucher better and cleaner approach is to loop on the higher level instead fo the lower level. - July 27, 21
* P118. Pascal's Triangle - I did it by inserting an element one by one for each row. A better solution I saw modified a copy of the last row, adding the last two entries and starting from the last element to avoid inserting 1 at the beginning. - July 27, 21
* P124. Binary Tree Maximum Path Sum. I dfs the tree, store max path sum that ends at this node in node->val and the recursive function returns the max path (any kind). A smarter solution I read defines helper function that only returns path sum that ends here, but updates a reference to the max sum of any path. Aug 6, 21
* P128. Longest Consecutive Sequence. Hash map. Aug 7, 21
* P129. Sum Root to Leaf Numbers. Backtracking. Aug 2, 21
* P133. Clone Graph. I though my solution of iterative DFS would be really slow, but it ended up having a decent run time. Other solutions are BFS with a queue and DFS with recursion. Aug 5, 21
* P136. Single Number - Initially, I didn't know it's bit manipulation and had a hard time figuring out a solution of linear time and constant space. It never occurred to me XOR is commutative haha. 
* P139. Word Break. I did it with dp but I saw an interesting solution using BFS with a queue. Aug 4, 21
* P141. Linked List Cycle - It’s the easier version of a problem I did yesterday or on Thursday. July 31, 21
* P142. Linked List Cycle II -  I did using O(n) space, which is poor. Then I read a genius solution that uses two pointers. It's like two cars racing each other. - July 30, 21
* P143. Reorder List. Three steps. I thought I was pretty smart for coming up with a way to find mid point in one pass, but that just turned out to be the most common way of doing it haha. Aug 11, 21
* P144. Binary Tree Preorder Traversal. Basic. Aug 2, 21
* P150. Evaluate Reverse Polish Notation - I finished very quickly but one sample test wouldn’t pass and I spent so much time debugging it! I tried getting vscode c++ debugger to work but something was missing for arm64 and then I thought i should use lldb on command line. Just when I was about to do that, I realized that I’d been treating negative numbers as the minus operator! I solved it without using a stack, I used recursion instead. I used a pointer (actually reference) to represent the end of the subarray so I didn’t have to modify the given vector.  July 30, 21
* P153. Find Minimum in Rotated Sorted Array. Binary search. Did the harder version before. Aug 7, 21
* P169. Majority Element. I usd nth element, but I saw many different solutions to this question: divide and conquer, Moore’s voting algorithm (very smart) and even bit manipulation! July 31, 20
* P191. Number of 1 Bits. I did it by repeatedly clearing the lowest set bit. Other ways include keep dividing by two. Aug 7, 21
* P198. House Robber. Only need to look at the last two, pretty easy. Aug 9, 21
* P199. Binary Tree Right Side View. Did it with BFS, then redid the question with DFS. Aug 12, 21
* P200. Number of Islands -  I did it with dfs, with seems standard. July 30, 21
* P205. Isomorphic Strings - I stored character replacement in two maps but it's not fast enough, and better solutions store the last seen position of pair in two vectors. I like how it has dp flavor in it. - July 29, 21
* P206. Reverse Linked List. I did it with iteration but I learned how to do it recursively from discussions - the key is that head points to the end of the reversed rest of the list. Aug 5, 21
* P207. Course Schedule. I used dfs. Kahn’s algorithm is much smarter. July 31, 20
* P213. House Robber II. Use rob 1. Aug 11, 21
* P215. Kth Largest Element in an Array. I used make_heap keeping a heap of size roughly n but I learned that I can also use a min heap to keep track of the largest k elements, and that functions partial_sort and nth_element exist. July 31, 20
* P217. Contains Duplicate. Pretty easy. Aug 5, 21
* P226. Invert Binary Tree - I used recursion at first then redid the problem with queue/BFS. July 26, 2021
* P230. Kth Smallest Element in a BST. Aug 10, 21
* P231. Power of Two.  Aug 10, 21
* P235. Lowest Common Ancestor of a Binary Search Tree. Aug 11, 21
* P236. Lowest Common Ancestor of a Binary Tree. I did it by defining another dfs function to traverse the tree, but I saw a great solution that exapands the meaning of the solution function. July 31, 21
* P238. Product of Array Except Self. The solution I came was the same as the top voted one, used contant space and O(n) time. Aug 6, 21
* P242. Valid Anagram. Sort and compare or store in map. Aug 6, 21
* P268. Missing Number. Fun bit manipulation. Aug 2, 21
* P283. Move Zeroes. Aug 12, 21
* P300. Longest Increasing Subsequence. I used dp with in n squared time but it’s really slow on the tests. I learned that the nlogn method keeps values in the resulting array/vectors as small as possible. Aug 1, 21
* P322. Coin Change. DP problem. Changing vector to array makes it so much faster. Since I didn’t need to add elements to the vector,  I should have used array to begin with. Aug 5, 21
* P328. Odd Even Linked List. Straightforward. Aug 1, 21
* P338. Counting Bits. I did it in O(n) time in one pass using k/2. I saw another solution that keeps track of the highest set big, which updates at 1, 2, 4, 8…, which is very cool. Aug 1, 21
* P347. Top K Frequent Elements. I used heap, but bucket sort seems faster. Aug 2, 21
* P371. Sum of Two Integers. I learned a lot from a discussion post that reviewed many different bit manipulation problems. I think it even covers more stuff than EPI’s chapter 2 does. Aug 5, 21
* P377. Combination Sum IV. I made an array of int to store dp subproblem results, but int is not big enough sometimes. Unsigned int fixes it. Aug 7, 21
* P389. Find the Difference. Aug 10, 21
* P404. Sum of Left Leaves - I used recursion, but could have used a stack for iteration. July 28, 2021
* P435. Non-overlapping Intervals. My solution is asymptotically fast as the fast solutions (the sample solutions from the top percentile), nlog(n). Actually my solution is almost exactly the same as the sample solution that finished in 0ms (if anything, mine should be faster in theory). However, mine finish in around 400ms! I copied and pasted two very fast sample solutions (0ms and 4ms) and submitted those, but strangely they also finished in around 400ms. Aug 9, 21
* P448. Find All Numbers Disappeared in an Array - I did it in the most straightforward way, so O(n) time and O(n) space, but the good solutions negate values at indices that appear in the array, very smart. July 29, 21
* P454. 4Sum II. I ‘merged’ the first two and then iterate over the last two to find quadruples, and it’s a pretty common method. Aug 3, 21
* P525. Contiguous Array. I keep track of the difference between numbers 0’s and 1’s in \[0, k). Then find the pair with same difference that’s farthest apart, which happened to be the standard method haha. Aug 3, 21
* P572. Subtree of Another Tree - I did it with a straghtforward recursion, but a smarter method I saw converted both trees to strings and check if the shorter one is a substring. July 30, 21
* P557. Reverse Words in a String III - Two iterators solved it. There are solutions in other languages using built-in string functions, but that’s not the case for C++. July 30, 21
* P589. N-ary Tree Preorder Traversal. Just a dfs question. Aug 1, 21
* P605. Can Place Flowers. Greedy. Aug 1, 21
* P617. Merge Two Binary Trees. Recursion. Aug 3, 21
* P654. Maximum Binary Tree. I resisted the temptation to split the array and build two subarrays. From other solutions, I learned that it’s more convenient to build wrong connections between parents and children and then update them to the correct ones when pushing a new element.  Aug 12, 21
* P658. Find K Closest Elements. I did it by finding the closest element first and then finding the next closest element, very boring. A much more interesting solution is the top-voted one, which treats the result as a slider window and performs a modified binary search, very smart. Aug 3, 21
* P665. Non-decreasing Array. I could’ve use less conditions. Aug 3, 21
* P674. Longest Continuous Increasing Subsequence. DP in linear time, same as the stock question. Aug 4, 21
* P703. Kth Largest Element in a Stream. Two heaps. Aug 4, 21
* P763. Partition Labels.(so that each letter appears in at most one partition) I kept track of both low and high, but high alone is enough. Aug 4, 21
* P844. Backspace String Compare. Aug 12, 21
* P863. All Nodes Distance K in Binary Tree. I did it in a strange way, but I should, like other, do BFS with a parent map.Aug 12, 21
* P1143. Longest Common Subsequence. I used a 2D vector to store dp subproblem, but only a 1D vector is sufficient. Aug 7, 21 
* P1171. Remove Zero Sum Consecutive Nodes from Linked List. One pass. Same as the two top voted solutions. Aug 4, 21
* P1306. Jump Game III. DFS. Aug 2, 21
