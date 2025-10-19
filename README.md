
# Guess-the-target.
#This is a game.
import random
target=random.randint(1,100)


while True:
	user=int(input("Guess the target: "))
	if (user==target):
		print("Guess: the correct!")
		print("___GAME OVER___")
		break
	elif(user>target):
		print("your guess is greater than target.")
	else:
		print("your guess is smaller than target.")