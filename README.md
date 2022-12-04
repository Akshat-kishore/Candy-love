# Candy-love
# cook your dish here
for k in range(int(input())):
    a=int(input())
    s=list(map(int,input().split()))
    h=0
    for v in range(len(s)):
        h=h+s[v]
        
    if h%2==1:
        print("YES")
    else:
        print("NO")
