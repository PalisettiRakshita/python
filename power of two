class Solution:
    def isPowerOfTwo(self, n: int) -> bool:
        if n==1:
            return True
        elif n%2==1:
            return False
        else:
            return n>1 and self.isPowerOfTwo(n//2)
