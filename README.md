# Lives-System
life=0
while life < 3:
    print(life)
    i = input("Choose Y or No.....   ")
    if i == 'yes':
        print("You choose yes")
        life += 1
          
    elif i == 'no':
        print("YOu chose no")
        life -= 1
        
    else:
        life -=5
        print("CHeat code activiated")
          
print('\n')
print('THis is while True loop')
life = 0
while True:
    print(life)
    life += 1
    if life == 3:
        break
print('THe while loop ended!')
