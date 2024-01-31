import random
print("Enter the lower limit and higher limit of your choice in the game respectively:")
lower= int(input())
upper= int(input())
print("You have only 7 guesses to find what is the random number that the computer has used:")
# now create a certain variable that can save that random number produced by computer
x = random.randint(lower, upper)
guess = 0
# now create a range in which allows only a certain number of moves to win.
for i in range(0,7):
    #using int() ensures that the datatype at runtime would be int and wont cause errors with the comparison operators.
    guess = int(input())
    if (x== guess):
        print("You have guessed the number correctly.")
        break
    elif(x>guess):
        print("You have guessed the number too low.")
    elif(x<guess):
        print("You have guessed the number too high.")
print("Thank you for playing high and low with us. (^.^)")
