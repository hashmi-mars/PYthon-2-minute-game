# PYthon-2-minute-game
just a small 2 minute game - where I am teaching my students to make Python Conditions and If statements
print("Let's play a game")
print("You choose a number and this program would tell you the colour hiding under your number")
print("You should choose from 1 to 4, otherwis it would give an error")

a =  int(input("Please choose a number between 1 and 4"))

if a == 1:
    print("Green")
elif a == 2:
    print("Red")
elif a == 3:
    print("blue")
elif a == 4:
    print("Yellow")
else:
    print("Error, you didn't choose right option")
