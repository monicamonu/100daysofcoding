## Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.
```
Example input #1
1
1
1
2
2
2

Example output #1
3661

Example input #2
1
2
30
1
3
20

Example output #2
50
```
hour=int(input())
minutes=int(input())
seconds=int(input())
hr1=int(input())
min1=int(input())
sec1=int(input())

total_seconds1 = (hour * 3600+(minutes * 60 +(seconds*1)))
total_seconds2 = (hr1 * 3600 + (min1 * 60 + (sec1*1))) 

tot_sec = total_seconds2 - total_seconds1

print(tot_sec)



