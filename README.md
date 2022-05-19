# Ass-2-18-5-22
Assignment-2
class Solution:
    def subarraysDivByK(self, nums: List[int], k: int) -> int:
        rs=ans=0
        dp={0:1}
        for A in nums:
            rs+=A
            key=rs%
            if key in dp:
                ans+=dp[key]
                dp[key]+=1
            else:
                dp[key]=1

        return ans
