b=int(input())
c=0
v=0
for n in range(b+1):

    if(n>1):
        def isPrime(n):
            for i in range(2,int(n**0.5)+1):
                if (n%i==0):
                    return False
        
            return True
   
        if(isPrime(n)):
            c=c+n
            
            if(isPrime(c) and c<b):
                
                v=v+1
            elif(c>b):
                break

print(v-1)
