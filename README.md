# rock-paper-scissor
import random
player=int(input("Enter  0 for rock, 1 for paper,and 2 for scissor: "))
computer=random.randint(0,2)
print(f"{computer}")
if player>=3 or player<0:
    print("number is inavlid you lose")
elif player==0 and computer==2:
    print("You Win!")
elif player==2 and computer==0:
    print("You lose")
elif computer>player:
    print("You lose!")
elif computer<player:
    print("You win!")
elif computer==player:
    print("draw")
