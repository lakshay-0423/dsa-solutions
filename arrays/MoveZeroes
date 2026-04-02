// Problem: Move Zeroes
// Link: https://leetcode.com/problems/move-zeroes/
// Difficulty: Easy
// Approach: Two pointers - i tracks zero, j finds next non-zero to swap
// Time: O(n) | Space: O(1)

class Solution {
    public void moveZeroes(int[] nums) {
        int n=nums.length;
        int i=0,j=0;
        while(i<n && j<n){
            if(nums[i]==0 && i!=j){
                nums[i]=nums[j];
                nums[j]=0;
            }
            if(nums[i]!=0) i++;
            j++;
        }
    }
}