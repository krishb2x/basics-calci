# basics-calci

# building a calculater
def add(x,y):
    return x+y

def sub(x,y):
    return x-y

def mult(x,y):
    return x*y

def divide(x,y):
    return x%y

print('Select operation:')

print('1.add')
print('2.sub')
print('3.mult')
print('4.divide')

while True:
    choice=input('enter choice(1/2/3/4):')
    if choice in ('1','2','3','4'):
        a= float(input("enter the frist number!"))
        b=float(input("enter the second number!"))
        if (choice=='1'):
            print(a,"+",b,"=",add(a,b))
            break
        elif(choice =='2'):
            print(a, "-", b, "=", sub(a, b))
            break
        elif (choice == '3'):
            print(a, "*", b, "=", mult(a, b))
            break
        elif (choice == '4'):
            print(a, "%", b, "=",divide (a, b))
            break
