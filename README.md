# 5-Line-Dice-Roller
A 5 Line dice roller
````python
import random
print (input("DICE ROLLER! PRESS ENTER TO ROLL: "))
num = "1 2 3 4 5 6"
x = num.split()
print (random.choice(x))
````
Update it can be a 4 line Dice Roller
````python
import random
print (input("DICE ROLLER! PRESS ENTER TO ROLL: "))
num = ["1","2","3","4","5","6"]
print (random.choice(num))
````
