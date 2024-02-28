n=int(input())
for i in range(n):
  a,b,c=map(int, input().split())
  z=(a+b)/2
  if(z>c):
       print("YES")
  else:
       print("NO")


