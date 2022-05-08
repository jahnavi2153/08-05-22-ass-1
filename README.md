# 08-05-22-ass-1
#Write a program to store no for odd keys and yes for even numbers and display them.
l=[]
d={}
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
y=1 
for i in l:
    if i%2==0:
        d[i]='Yes'
    else:
        d[i]='No'
print(d)

output:
5
21
35
44
67
68
{21:'No',35;'No',44:'Yes',67:'No',68:'Yes'}
