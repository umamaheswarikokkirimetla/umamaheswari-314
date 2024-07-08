class Solution:
    def rearrangeArray(self, nums: List[int]) -> List[int]:
        n=len(nums)
        pos=[]
        neg=[]
        for i in range(n):
            if nums[i]>=0:
                pos.append(nums[i])
            if nums[i]<0:
                neg.append(nums[i])
        for i in range(n//2):
            nums[2*i]=pos[i]
            nums[2*i+1]=neg[i]
        return nums
        
