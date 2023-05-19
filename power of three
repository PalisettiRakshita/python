class Solution:
    def isPowerOfThree(self, n: int) -> bool:
        if n==1:
            return True
        elif n%3>=1:
            return False
        else:
            return n>1 and self.isPowerOfThree(n//3)
