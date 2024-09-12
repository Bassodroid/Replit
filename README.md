# 100 Days Of Code

Here I will track my progress doing Replit's 100 Days Of Code Challenge

# Table of Content
- [Day 1](#day-1)
- [Day 2](#day-2)
- [Day 3](#day-3)

## Description

In this course, I will build games, apps, and websites by mastering Python programming. I will build 100 projects in 100 days.

## Getting Started

### Languages

During the challenge, I will be using Python to complete objectives.

## Authors

Contributors names and contact info

BassoDroid  
[Replit](https://replit.com) 

## Day 1

## Description

### Project 1: Print into the World

Let's get started with your first project! After only one day, you already have something you can share with the world.

You can continue to use this same repl for your project. Just make sure you delete any previous code from our practice session.

- Write your full name and today's date in separate lines of code.
  
- Copy this text below. See if you can do it with just the one print statement!
  
- On the next line add I am feeling with an emoji of your choice to illustrate how you're feeling about the challenge.

- Add one more line to your output You can follow my progress at replit.com/@ and add in your Replit username. This will be a great way of maintaining accountability for yourself!

- Run your program.

### Code

```
print("Basso Droid")
print("September 08, 2024")
print("""I am signing up for Replit's 100 days of Python challenge!
I will make sure to spend some time every day coding along, for a minimum of 10 minutes a day.
I'll be using Replit, an amazing online IDE so I can do this from my phone wherever I happend to be. 
No excuses for not coding from the middle of a field!""")
print("I am feeling 😊")
print("You can follow my progress at replit.com/@BassoDroid")
```

## Day 2

## Description

### 👉 Day 2 Challenge: Getting to Know You Project

Write code that does the following:

- Asks for the user's name, favorite food, favorite music and where they live (or you can create other questions!)

- Store all of the answers in different variables.

- Print out a full sentence that includes the user's favorite things.

- Give them a positive affirmation at the end - tell them they rock at doing something!

### Code

```
print("Getting to know you!")
print()
myName = input("What's your name?: ")
myFood = input("What's your favorite food?: ")
myMusic = input("What's your favorite music?: ")
myLocation = input("Where do you live?: ")
print(f"You are \n {myName} \n You're probably hungry for \n {myFood} \n and you're definitely getting your groove on to \n {myMusic} \n living in the amazing \n {myLocation}")
```

## Day 3

## Description

### 👉 Day 3 Challenge: The Ultimate Wacky Recipe Maker

We have learned enough skills for a simple, but cool, project!

Remember when you were a kid and thought the ideal dinner would just be all your favorite things mixed in a bowl? How did that Nutella Mac & Cheese taste? Well - let's come up with a recipe generator to build us an amazing dish for today's evening meal!

You will need to:

- Create these as a variable:
  - A type of food
  - A type of plant
  - A method of cooking
  - A word to describe burned food
  - A household item

- Output a nice looking Recipe page that *concatenates* a dish in this format:
  - cooking food with burned plant on a bed of item
 
EXTRA: Remix your recipe to include more variables and a wackier type of dish.

Why not step it up and create a recipe for a starter, main course and dessert?

### Code

Initial: 

```
# The Ultimate Wacky Recipe Maker

# This is a program that will create a recipe from user input. Silly, right?

foodName = input("Name a food: ")
plantName = input("Name a type of plant: ")
cookingMethod = input("How should we cook the meal? Sauted, baked, or fried -- You choose!: ")
burnedFood = input("How would you describe burned food?: ")
householdItem = input("Name a household item: ")
print()
print("MENU")
print(cookingMethod, foodName, "with", burnedFood, plantName, "on a bed of", householdItem)
```

Extra:

```
# The Ultimate Wacky Recipe Maker

# This is a program that will create a recipe from user input. Silly, right?

# Updated for extra prompts. Added starter, main course, and dessert prompts.

# This is the starter prompt.

try_again = "yes"

print("""Thank you for using the Ultimate Wacky Recipe Maker! \n
We've updated some features to make this program even more wacky!\n""")
print("To begin, please decide on a course: either starter, main course, or dessert. \n")

while try_again != "no":
  recipe_type = input("Which course would you like to make?: ")
  
  if recipe_type == "starter" or recipe_type == "main course":
    print(f"""Great! Let's get started on your {recipe_type} recipe!\nWe'll need to decide 
    some yummy, and very wacky ingredients!\n""")
    
    dish_name = input("Let's name your dish. What would you like to call your dish?: ")
    
    print("Awesome! Let's get started on your " + dish_name + "!\n")
    
    food_name = input("First, we'll need to add some food. What should we add?: ")
    plant_name = input("Cool, cool. Now we need to add some earthy flavor. Pick a plant: ")
    cooking_method = input("""Awesome! Now we need to decide how we're going to cook this. 
    Sauted, baked, or fried? -- You choose!: """)
    burned_food = input("""Now, I am usually a great chef, but just in case, 
    how would you describe burned food?: """)
    
    print(f"Ooof, {burned_food}; that's certainly a colorful way to describe burned food!\n")
    
    household_item = input("""Now, all great chefs know that plating is the first impression. 
    We'll need a household item for that. What should we add?: """)
    
    print("Ooooh! That'll definitely do it! Let's see what we have here...\n")
    print(f"Fire in the kitchen!!\n Here's your new {recipe_type} recipe:\n")
    print(f"""Menu \n {dish_name} \n {cooking_method} {food_name} with {burned_food}
    {plant_name} on a bed of {household_item}\n How's that for wacky!?\n""")
    
    try_again = input("Would you like to try again? (yes/no): ")
    
  elif recipe_type == "dessert":
    print(f"""Great! Let's get started on your {recipe_type} recipe!\n
    We'll need to decide some yummy, and very wacky ingredients to create something 
    sweet to close out your menu!\n""")
    
    dish_name = input("Let's name your dish. What would you like to call your dish?: ")
    
    print("Awesome! Let's get started on your " + dish_name + "!\n")
    
    food_name = input("First, we'll need to add some food. What should we add?: ")
    plant_name = input("Cool, cool. Now we need to add some earthy flavor. Pick a plant: ")
    cooking_method = input("""Awesome! Now we need to decide how we're going to cook this.
    Sauted, baked, or fried? -- You choose!: """)
    burned_food = input("""Now, I am usually a great chef, but just in case, 
    how would you describe burned food?: """)
    
    print(f"Ooof, {burned_food}; that's certainly a colorful way to describe burned food!\n")
    
    household_item = input("""Now, all great chefs know that plating is the first impression. 
    We'll need a household item for that. What should we add?: """)
    
    print("Ooooh! That'll definitely do it! Let's see what we have here... \n")
    print(f"Fire in the kitchen!! \nHere's your new {recipe_type} recipe: \n")
    print(f"""Menu \n {dish_name} \n {cooking_method} {food_name} with {burned_food}
    {plant_name} on a bed of {household_item}\n How's that for wacky!?\n""")
    
    try_again = input("Would you like to try again? (yes/no): ")
    
  else:
    print("Sorry, we don't have that course. Please try again.\n")
    
    try_again = input("Would you like to try again? (yes/no): ")
    
  print("\nThank you for using the Ultimate Wacky Recipe Maker! \nBye bye!")
```

