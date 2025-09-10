class Solution {
public:
    void rotate(vector<int>& nums, int k) {
        int n=nums.size();
        k=k%n;
        auto reverseArr =[&](int l,int r){
            while(l < r){
                swap(nums[l],nums[r]);
                l++;
                r--;
            }
        };
    
    reverseArr(0,n-1);
    reverseArr(0,k-1);
    reverseArr(k,n-1);
    }
};
