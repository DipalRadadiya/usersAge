# usersAge
Write a Python program that takes a user's age as input and prints "You are a minor" if the age is less than 18, otherwise, it should print "You are an adult."
# Get the user's age as input
user_age = int(input("Enter your age: "))

# Check if the user is a minor or an adult
if user_age < 18:
    print("You are a minor.")
else:
    print("You are an adult.")

Enter your age: 17
You are a minor.
Enter your age: 50
You are an adult.
