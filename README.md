# RedistributingChocolates
# cook your dish here
t=int(input())
while t:
    a,b,c=map(int,input().split())
    s=a+b+c
    if(s%2==0 and s%3==0):
        print('yes')
    else:
        print('no')
    t-=1
