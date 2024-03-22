from random import randint
n=int(input("please enter a number"))
rand=randint(1,100)
print("com: ",rand)
while True:
    add=input("player :")
    if add=="hop":
        if(rand+1)%n==0:
            add=str(rand+1)
        else:
            print("game over**")    
    elif int(add)==(rand+1) and (int(add)%n)!=0 :
        int(add)==(rand+1)
    else:
        print("game over") 
        break
    add1=int(add)+1
    if add1 % n == 0 :
        print("com : hop")
    else:
        print("com :",add1)
    rand+=2        
