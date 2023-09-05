# PerfectTrio
# cook your dish here
for i in range(int(input())):
    a,b,c=map(int,input().split())
    if(a+c==b or a+b==c or b+a==c or b+c==a):
        print('YES')
    else:
        print('NO')
