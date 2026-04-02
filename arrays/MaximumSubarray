// Problem: Maximum Subarray
// Link: https://leetcode.com/problems/maximum-subarray/
// Difficulty: Medium
// Approach: Kadane's Algorithm - track running sum, reset to 0 if negative, update max throughout
// Time: O(n) | Space: O(1)

class Solution {
    public int maxSubArray(int[] nums) {
        int maxSum=nums[0];
        int sum=0;
        for(int i=0;i<nums.length;i++){
            sum+=nums[i];
            maxSum=Math.max(sum,maxSum);
            if(sum<0) sum=0;
        }
        return maxSum;
    }
}
