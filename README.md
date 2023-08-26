# Cyclic-Quadrilateral
# cook your dish here
t = int(input())
for i in range(t):
  a,b,c,d = map(int,input().split())
  print("yes") if (a+c and b+d)==180 else print("no")
