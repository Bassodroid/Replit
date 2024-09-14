# 100 Days Of Code

Here I will track my progress doing Replit's 100 Days Of Code Challenge

# Table of Content
- [Day 1](#day-1)    |  [Day 6](#day-6)
- [Day 2](#day-2)    |  [Day 7](#day-7)
- [Day 3](#day-3)    |  [Day 8](#day-8)
- [Day 4](#day-4)    |  [Day 9](#day-9)
- [Day 5](#day-5)    |  [Day 10](#day-10)

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

## Day 4

## Description

### 👉 Day 4 Challenge: Everyone loves a good story!

Well, you're going to create your own adventure story that places your user in the role of the main character and we'll even customize the story to suit their interests.

Your task

- Ask your users to list a bunch of information about them: things they like, things they hate, names of family and friends... it's up to you how many and what kinds of things you pick. Keep it wacky!

-  Now construct your story - it can be about anything you want, but must use the variables you've created in step 1.

-  Make sure to only work one paragraph at a time. Otherwise things could get a bit messy.

Sneaky Extra Skill

You can jazz things up even more by changing the color of the text. Wow. We're quickly approaching the quality of output of a computer from 1981! 😬

How does it work?

It's all just print statements, but using special codes that tell your console to start printing everything after this point in the new color.
You will need to reset if you want to go back and change it in previous lessons.

| Color    | Value    |
| -------- | -------- |
| Default  | 	      0 |
| Black    |	     30 | 
| Red	     |       31 |
| Green	   |       32 |
| Yellow   |       33 |
| Blue     |	     34 |
| Purple   |	     35 |
| Cyan     |	     36 |
| White	   |       37 |

### Code

```

# This is a simple program that will create a story based on user input. 

# Intro

print("""Welcome to your adventure simulator. I am going to ask you a bunch of questions
and then create an epic story with you as the star!\n""")

# Variables

name = input("What is your \033[34mname\033[0m? ")
age = input("How \033[32mold\033[0m are you? ")
food = input("What is your favorite \033[33mfood\033[0m? ")
color = input("What is your favorite \033[31mc\033[32mo\033[33ml\033[34mo\033[35mr\033[0m? ")
animal = input("What is your favorite \033[36manimal\033[0m? ")
num_family = input("How many people are in your \033[35mfamily\033[0m? ")
gear_grinder = input("What is something you \033[31mdislike\033[0m? ")
super_power = input("If you could have a \033[40msuper power\033[0m, what would it be? ")

# Here I realized that I wanted the value for the color variable to match the color of 
# the text in the input query. Therefore, I had to think of a way to add color to the 
# string for each character. I chose to use a for loop to iterate through the string and 
# add the color to each character.


asci_code = 31
color_coded = ""

for char in color:
  color_coded += f"\033[{asci_code}m{char}\033[0m"
  asci_code += 1

# Story

print(f"""\nHello \033[34m{name}\033[0m!

After \033[32m{age}\033[0m years of age you discovered that you have the power of 
\033[40m{super_power}\033[0m. You travel the globe saving \033[36m{animal}\033[0m from \033[31m{gear_grinder}\033[0m. 
But in your spare time you and your \033[35m{num_family}\033[0m family members rent out a 
{color_coded}\033[0m beach house and run a stand selling \033[33m{food}\033[0m.""")

```

#### Added a while loop for repeatablity

```
# This is a simple program that will create a story based on user input. 

# Intro

try_again = "yes"
while try_again == "yes":
  print("""Welcome to your adventure simulator. I am going to ask you a bunch of questions
and then create an epic story with you as the star!\n""")

# Variables

  name = input("What is your \033[34mname\033[0m? ")
  age = input("How \033[32mold\033[0m are you? ")
  food = input("What is your favorite \033[33mfood\033[0m? ")
  color = input("What is your favorite \033[31mc\033[32mo\033[33ml\033[34mo\033[35mr\033[0m? ")
  animal = input("What is your favorite \033[36manimal\033[0m? ")
  num_family = input("How many people are in your \033[35mfamily\033[0m? ")
  gear_grinder = input("What is something you \033[31mdislike\033[0m? ")
  super_power = input("If you could have a \033[40msuper power\033[0m, what would it be? ")

# Here I realized that I wanted the value for the color variable to match the color of 
# the text in the input query. Therefore, I had to think of a way to add color to the 
# string for each character. I chose to use a for loop to iterate through the string and 
# add the color to each character.


  asci_code = 31
  color_coded = ""

  for char in color:
    color_coded += f"\033[{asci_code}m{char}\033[0m"
    asci_code += 1

# Story

  print(f"""\nHello \033[34m{name}\033[0m!

After \033[32m{age}\033[0m years of age you discovered that you have the power of 
\033[40m{super_power}\033[0m. You travel the globe saving \033[36m{animal}\033[0m from \033[31m{gear_grinder}\033[0m. 
But in your spare time you and your \033[35m{num_family}\033[0m family members rent out a 
{color_coded}\033[0m beach house and run a stand selling \033[33m{food}\033[0m.""")

  print("\nHow did you like that one? Think you might like to try again?")  
  try_again = input("\nYes? No? ")
print("\nAlright, thanks for playing!")
```

## Day 5

## Description

### 👉 Day 5 Challenge: "Which character are you?" Generator

You will need to:

- Ask your users a series of questions that identify if they're one of the characters in the world you have created.

- Add multiple if statements to check the result of each question.

- Make sure to have a final print if they haven't selected any of the characters so far.

## Code

```

# Which Character Are You Generator?

# This will be loosely based on the characters from George RR Martin's "A Song of Ice and Fire."

# Character Variables
ned_stark = 'Ned Stark'
arya_stark = 'Arya Stark'
sansa_stark = 'Sansa Stark'
jon_snow = 'Jon Snow'
daenerys_targaryen = 'Daenerys Targaryen'
tyrion_lannister = 'Tyrion Lannister'
littlefinger = 'Littlefinger'
the_hound = 'The Hound'

# Intro
print('Game of Thrones Character Generator')
print('------------------------------------')
print('Answer the following questions to find out which character you are!')
print('------------------------------------')
print('Please answer the following questions using either Yes or No.')
print('------------------------------------')

start = input("Alright, here's your first one, are you ready? ")

while start == 'Yes':
    ambitious = input('Do you have a desire for power and influence? Are you constantly seeking to advance? ')
    if ambitious == 'Yes':
        calculating = input('Do you like to play chess? Do you think plans through several steps ahead? ')
        if calculating == 'Yes':
            ruthless = input('Are you determined to meet your goals no matter the cost? ')
            if ruthless == 'Yes':
                print('You are ' + littlefinger + '!')
            else:
                print('You are ' + tyrion_lannister + '!')
        else:
            curious = input('Do you like adventure and exploration? Do you like to learn new things? ')
            if curious == 'Yes':
                honorable = input('Do you believe in honor and duty? ')
                if honorable == 'Yes':
                    loyal = input('Do you always try to keep your promises? ')
                    if loyal == 'Yes':
                        print('You are ' + jon_snow + '!')
                    else:
                        print('You are ' + tyrion_lannister + '!')
                else:
                    print('You are ' + daenerys_targaryen  + '!')
            else:
                print('You are ' + arya_stark + '!')
    else:
        curious = input('Do you like adventure and exploration? Do you like to learn new things? ')
        if curious == 'Yes':
            rebellious = input('Do you tread out on your own path? Or do you often seek out a group? ')
            if rebellious == 'Yes':
                protective = input('Do you often want to protect your friends and family? ')
                if protective == 'Yes':
                    print('You are ' + arya_stark + '!')
                else:
                    print('You are ' + sansa_stark+ '!')
            else:
                reserved = input('Do you tend to keep to yourself? ')
                if reserved == 'Yes':
                    honorable = input('Do you believe in honor and duty? ')
                    if honorable == 'Yes':
                        print('You are ' + ned_stark + '!')
                    else:
                        print('You are ' + littlefinger + '!')
                else:
                    print('You are ' + tyrion_lannister + '!')
        else:
            compassionate = input('Do your friends often rely on you for advice? Do you prefer to listen and help others? ')
            if compassionate == 'Yes':
                protective = input('Do you often want to protect your friends and family? ')
                if protective == 'Yes':
                    print('You are ' + daenerys_targaryen + '!')
                else:
                    print('You are ' + arya_stark + '!')
            else:
                print('You are ' + the_hound + '!')

    start = input("How'd we do? Do you think you might be a different character? ")

    if start == 'No':
        print('Great! Thanks for playing!')
        break
    else:
        print('Let\'s try again!')
print('Awww, too bad! Come back when you\'re ready!')

```




