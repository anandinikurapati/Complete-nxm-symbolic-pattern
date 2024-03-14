# Complete-nxm-symbolic-pattern
# Approach - 1
r = int(input())
c = int(input())
for i in range(r):
  for j in range(c):
    print("*",end=" ")
  print()
# Approach - 2
a = []
r,c = map(int,input().split())
for i in range(r):
  x = []
  for j in range(c):
    x.append("*")
  a.append(x)
for i in a:
  print(*i,sep=" ")
# Approach - 3
r = int(input())
c = int(input())
for i in range(r):
  print("* "*c)
