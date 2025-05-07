# Guessing-a-Random-Number

import random
target=random.randint(1,100)

while True:
    userChoice=input("Guess the Target or Quit  :")
    if(userChoice == "Quit"):
        break
    userChoice =int(userChoice)
    if(userChoice == target):
        print("U have Guess the Number Correctly")
        break
    elif(userChoice < target):
        print("U have Guess the Number too Small, Guess the Higher Number")
    else:
        print("U have Guess the Number Higher, Guess the Lower Number")
        
print("GAME OVER THANKS FOR PLAYING A GAME")
