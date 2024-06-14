# Python-to-find-primary-number 
def primNum(x: int):
    if x<=1:
       print(f"{x} is not a prime number.")
       return
    if x==2 :
        print ("2 is prime number")
        return 
    
    count=0   
    for I in range(2,round(x/2)):
        if x%I==0:
            count+=1
            
    if count >=1 :
         print ("not prim")  
    else:
         print("yes prim")
        
primNum(5)
