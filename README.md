# Leetcode

- Easy

    - **0001 Two Sum**
    
        Interesting! Not the a+b problem. Use dictionary to record the pair of numbers.
    
    - **0007 Reverse Integer**
    
        With the help of string, we can reverse the number directly. Pay attention to the bound and negative sign.
    
    - **0009 Palindrome Number**
    
        Still with the help of string.
    
    - **0013 Roman to Integer**
        
        First sum up the naive numbers and then substract the special combinations.
        
    - **0014 Longest Common Prefix**
    
        Compare the adjacent string and find common prefix. Pay attention to the empty strings.
        
    - **0020 Valid Parentheses**
    
        Use stack to store parentheses. Pay attention to the order of the pair, that is, ")(" is not acceptable.
        
    - **0021 Merge Two sorted Lists**
    
        Compare the first number in the remaining lists.
    
    - **0026 Remove Duplicates from Sorted Array**
        
        Only need to return the length. Pay attention to the empty list.

    - **0027 Remove Element**
        
        Similar to P0026.
        
    - **0028 Implement strStr**
    
        KMP algorithm. First calculate next function, then match 2 string. The structure of this 2 procedure are almost similar. That is, if current character matches, then compare next; otherwise, let j back to the "next position".
        
    - **0035 Search Insert Position**
    
        Binary Search!
        
    - **0038 Count and Say**
    
        Just translate the statement.
        
    - **0053 Maximum Subarray**
    
        Use greedy algorithm to get $O(n)$. Pay attention to the case where all elements are negative. Divide and conquer can get $O(n\log n)$ but more subtle.
        
    - **0058 Length of Last Word**
    
        1. Ignore the space at the end of string. 
        2. Reverse the string and find the first space. Pay attention to string that consists of all spaces or only 1 word.
    
    - **0066 Plus One**
    
        High precision addition.
        
    - **0067 Add Binary**
    
        Also high precision addition.
        
    - **0069 Sqrt(x)**
    
        Use binary search to find the sqrt, 0/1 need to be considered seperately.
        
    - **0070 Climbing Stairs**
    
        Fibonacci series.
        
    - **0083 Remove Duplicates from Sorted List**
        
        Manage the list, need to pay attention to the empty node case.
        
    - **0088 Merge Sorted Array**
        
        Need to pay attention to the copy of array, cannot use such code ```a = a[:-1]```.
        
    - **0100 Same Tree**
        
        Recursion.
        
    - **0101 Symmetric Tree**
        
        Recursion as Same Tree, but just in mirror.
        
    - **0104 Maximum Depth of Binary Tree**
        
        Recursion to find the depth.
    
    - **0107 Binary Tree Level Order Traversal II**
        
        Remember the reverse order and pay attention to the empty tree.
        
    - **0108 Convert Sorted Array to Binary Search Tree**
        
        Use binary split to generate BST.
    
    - **0110 Balanced Binary Tree**
        
        First find the depth of each node and the justify whether it is balanced.
    
    - **0111 Minimum Depth of Binary Tree**
        
        The recursion is not only the minimal depth of children + 1, if the nodes do not have 2 children, then the depth should be the longest path.
        
    - **0112 Path Sum**
    
        The path should end at the nodes who do not have children nodes, aka leaf nodes. An empty tree does not have a value of 0.
        
    - **0118 Pascal's Triangle**
    
        Directly do the sum for adjacent elements.
        
    - **0119 Pascal's Triangle II**
    
        The same as 0118, pay attention to the function name.