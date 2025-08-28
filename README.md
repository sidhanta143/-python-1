# -python-1
project of python-1

import random
print("!...WEL_COME TO THE DIC_GAME...!")
while True:
 user=input("Are you sure to playing this game: ")
    if(user=="yes"):
        print("Ok..! Enjoy your game .. ")
    elif(user=="no"):
        print("Alright ..try again..!")
        break
    else:
        print("plz enter a valide answer..")

  system1=random.randint(1,6)
  system2=random.randint(1,6)

  print("The dice between 1 to 6 :",system1,system2)
