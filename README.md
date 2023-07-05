# RedistributingChocolates
# cook your dish here
t=int(input())
while t:
    a,b,c=map(int,input().split())
    s=a+b+c
    if(s>=6):
        print('yes')
    else:
        print('no')
    t-=1
