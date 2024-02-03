# Ejercicio1

n=int(input())
k=2
r=0
while k<n:
  if n%k==0:
    r=0
    break
  else:
    r=1 
    pass 
  k+=1

if r==1:print(f"el valor de n: {n} es primo" )
else: print(f"el valor de n: {n} no es primo" )


