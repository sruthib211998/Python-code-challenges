# Challenge 1
## In the number guessing game, the program selects a random number between two numbers, and the user guesses the correct number.

```py
import random
n=random.randrange(1,10)
guess=int(input("Enter any number:"))
while n!= guess:
    if guess < n:
        print("Too low")
        guess=int(input("Enter any number again:"))
    elif guess>n:
        print("Too high")
        guess=int(input("Enter any number:"))
    else:
        break
print("you guessed it right!")
```


