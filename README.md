# Frog-Jumping
```python
t=int(input())
for count in range(t):
    a,b,k=map(int,input().split())
    if k>=0 and k%2==0:
        print(k//2*(a-b))
    else:
        print((k-1)//2*(a-b)+a)
```
