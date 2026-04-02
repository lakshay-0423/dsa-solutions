// Problem: Two Sum
// Link: https://leetcode.com/problems/two-sum/
// Difficulty: Easy
// Approach: Brute Force - check every pair using nested loops
// Time: O(n²) | Space: O(1)

class Solution {

    public int[] twoSum(int[] nums, int target) {
        int len = nums.length;
        int[] arr = new int[2];
        for (int i = 0; i < len; i++) {
            for (int j = i + 1; j < len; j++) {
                if (nums[i] + nums[j] == target) {
                    arr[0] = i;
                    arr[1] = j;
                    return arr;
                }
            }
        }
        return arr;
    }
}
