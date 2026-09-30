# iam dipu mondol

H<sub>2</sub>O  
```
import random

secret_number = random.randint(1, 20)
print("I'm thinking of a number between 1 and 20.")

for attempts in range(1, 4):
    guess = int(input(f"Attempt {attempts}/3 - Take a guess: "))
    if guess == secret_number:
        print(f"You win! You guessed it in {attempts} tries.")
        break
else:
    print(f"Game over! The number was {secret_number}.")




````
