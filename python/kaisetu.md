##fullmoon
```
今日を 
1 日目とすると、今日以降で満月を見られる最初の日は 
M 日目です。以後は 
P 日ごと、つまり 
M+P 日目、
M+2P 日目、
… に満月を見られます。

1 日目から 
N 日目まで（両端を含む）の中で、高橋くんが満月を見られる日の数を求めてください。
```
```
n,m,p=map(int,input().split())
count=(n-m)//p+1
print(count)
p+1が必要な理由
n=10 m=2 P=3
(10-2)//3
=2となってしまう
最初のM日目に見た満月をカウントするためにp+1
```