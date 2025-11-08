# Triangle_prattern.py
Triangle pattern in Python using " for loops "✨
#upper piramid
n = int(input())
for i in range(1,n+1):     #if n=5 range=(1,5)after 1 loop +1
    for j in range(n-i):   #5-1=4
        print(" ",end="")  #prints out 4 spaces
    for k in range(2*i-1): #2*1-i=2*1-1;2-1=1 stars
        print("*",end="")          ###end=" " print() by default 
    print() #after loop next line  #ends with a newline (\n) 
                                   #makes to stay on smae lile

    
 
