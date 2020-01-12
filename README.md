
#this is a trial of code

#pattern printing
 
row = int(input())
k=1
for i in range(1,row+1):
    for j in range(1,i+1):
        print(k,end=' ')
        k+=1
    print('\n')
