# Python-Repository
import random

print("Guess The Number")
print("1. Easy (1-50)")
print("2. Medium (1-100)")
print("3. Hard (1-500)")

choice = input("Choose difficulty: ")

if choice == "1":
    limit = 50
elif choice == "2":
    limit = 100
else:
    limit = 500

number = random.randint(1, limit)
attempts = 0

while True:
    try:
        guess = int(input(f"Guess a number between 1 and {limit}: "))
        attempts += 1

        if guess < number:
            print("Too low!")
        elif guess > number:
            print("Too high!")
        else:
            print(f"You won in {attempts} attempts!")
            break
    except:
        print("Enter a valid number.")
