# Two Sum Question

Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.

 

Example 1:

```
Input: nums = [2,7,11,15], target = 9

Output: [0,1]

Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].
```

the first thing is to make sure the constraints,
need to ask the interviewer:

```
1. no negative integer?  //usually no
2. are there duplicate number?  //usually no
3. always a solution?  //usually no
4. if no solution, what should I return?  //empty array
5. only one solution?  // usually yes
```