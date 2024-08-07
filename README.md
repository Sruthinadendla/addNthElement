# addNthElement
def addNthElement(n,arr,k):
  sum=0
  for i in range(0,n):
    if((i+1)%k==0):
      sum=sum+arr[i]
  return sum
n=int(input())
arr=list(map(int,input().strip().split()))
k=int(input())
print(addNthElement(n,arr,k))
