# deepak
python coading
python ifelse
if __name__ =='__main__':
    n = int(input().strip())
    
    if n%2!=0:
       print("Weird")
            
    else:
         if n>=2 and n<=5:
            print("Not Weird")
         elif n>=6 and n<=20:
            print("Weird")
         elif n>20:
            print("Not Weird")
    

    
set.union
num1 = int(input())
setA = set(map(int, input().split()))
num1 = int(input())
setB = set(map(int, input().split()))
print(len(setA.union(setB)))
