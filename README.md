# macierz-28.01.21

from random import randint 
M=[[randint(1000,9999) for i in range(11)] for x in range(6)]
print(M)

min = M[0][0]
for i in range(6):
   for j in range(11):
      if M[i][j] < min :
         min = M[i][j]
print(min)

#lub 
 min = M[0][0]
 for lst in M:
     for elem in lst :
        if elem < min :
           min = elem 
 print(min)
