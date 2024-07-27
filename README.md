'''
   0 
  1 2 
 3 4 5 
6 7 8 9 
        ''' 
n=4
c=0
for i in range(1, n+1):
    for k in range(n,i,-1):
        print("", end=' ')
    for j in range(1, i+1):
        print(c, end=' ')
        c+=1
    print()
