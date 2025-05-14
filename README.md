# Question-no.-1550
Solution to the question no 1550 on leet code 

1550. Three Consecutive Odds
Given an integer array arr, return true if there are three consecutive odd numbers in the array. Otherwise, return false.


✅ Simple Explanation:
This Java method checks if there are three consecutive odd numbers in the given array.

🔍 How it works:
It loops through the array, stopping two elements before the end to avoid out-of-bounds access.

At each position i, it checks if:
arr[i], arr[i+1], and arr[i+2] are all odd numbers.

If it finds such a sequence, it returns true.

If no such sequence is found by the end of the loop, it returns false.

🧠 Example:
Input: [2, 3, 5, 7, 4]
Output: true  // because 3, 5, 7 are three consecutive odd numbers
