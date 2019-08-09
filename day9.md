## Given a three-digit number. Find the sum of its digits.

```
Example input
123

Example output
6
```
a=int(input())
sum=0
while a>0:
  dig=a%10
  a=a//10
  sum=sum+dig
print(sum)
