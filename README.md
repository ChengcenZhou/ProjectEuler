# ProjectEuler
#Problem 1

target=999
sum=0
for  i=1 to target do
if (i mod 3=0) or (i mod 5)=0 then sum:=sum+i
output sum

#Problem 2

limit=4000000
sum=0
a=1
b=1
while b<limit
   if b mod 2=0 then sum=sum+b
   h=a+b
   a=b
   b=h
output sum

#Problem 3
n=”the evil big number”
factor=2
lastFactor=1
while n>1
   if n mod factor=0
    then
      lastFactor=factor
      n=n div factor
      while n mod factor=0
         n=n div factor
   factor=factor+1
output lastFactor

#Problem 5

k = 20
N=1
i=1
check = true limit = sqrt(k) while p[i] <= k
     a[i] = 1
     if check then
           if p[i] <= limit then
                a[i] = floor( log(k) / log(p[i]) )
           else
                check = false
end if end if
     N = N * p[i] ^ a[i]
i=i+1 end while
output N

#Problem 6

limit = 100
sum sq = 0
sum = 0
for i = 1 to limit do
sum = sum + i
sum sq = sum sq + i2 end for
print sum2 − sum sq
