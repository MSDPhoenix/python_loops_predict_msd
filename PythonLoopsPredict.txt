# Create a .txt file. For each of the following code snippets, 
# write down your prediction of the output 
# #run the code snippet to see if you are correct

#1
for i in range(1, 10, 1):
    print(i)

#PREDICTED OUTPUT: 1,2,3,4,5,6,7,8,9

#ACTUAL OUTPUT: 1,2,3,4,5,6,7,8,9

#PREDICTION: CORRECT


#2
for t in range(1, 10, 3):
    print(t)

#PREDICTED OUTPUT: 1,4,7

#ACTUAL OUTPUT: 1,4,7

#PREDICTION: CORRECT


#3
for y in range(5):
    if y < 5:
        print(y)
    elif y == 3:
        print("y is 3")

#PREDICTED OUTPUT: 0,1,2,3,4 

#ACTUAL OUTPUT: 0,1,2,3,4

#PREDICTION: CORRECT


#4
for j in range(20, 1, -3):
    print(j)

#PREDICTED OUTPUT: 20,17,14,11,8,5,2

#ACTUAL OUTPUT: 20,17,14,11,8,5,2

#PREDICTION: CORRECT


#5
cities = ["London", "Paris", "Tokyo"]
for city in cities:
    print(city)

#PREDICTED OUTPUT:
# London
# Paris
# Tokyo 

#ACTUAL OUTPUT: 
# London
# Paris
# Tokyo 

#PREDICTION: CORRECT


#6
numbers = [7, 13, 8, 42]
for x in range(0, len(numbers)):
    print(x)
    print(numbers[x])
if numbers[len(numbers) - 1] == 42:
    print("The answer to life, the universe, and everything.")

#PREDICTED OUTPUT:
#0
#7
#1
#13
#2
#8
#3
#42
#The answer to life, the universe, and everything

#ACTUAL OUTPUT: 
#0
#7
#1
#13
#2
#8
#3
#42
#The answer to life, the universe, and everything

#PREDICTION: CORRECT


#7
for num in range(10):
    if num % 2 == 0:
        print("Hello")
    elif num % 4 == 0:
        print("World")
    else:
        print(num)

#PREDICTED OUTPUT:
# Hello
# 1
# Hello
# 3
# Hello
# 5
# Hello
# 7
# Hello
# 9

#ACTUAL OUTPUT: 
# Hello
# 1
# Hello
# 3
# Hello
# 5
# Hello
# 7
# Hello
# 9

#PREDICTION: CORRECT


#8
for num in range(10):
    if num % 4 == 0:
        print("Hello")
    elif num % 2 == 0:
        print("World")
    else:
        print(num)

#PREDICTED OUTPUT:
# Hello
# 1
# World
# 3
# Hello
# 5
# World
# 7
# Hello
# 9

#ACTUAL OUTPUT: 
# Hello
# 1
# World
# 3
# Hello
# 5
# World
# 7
# Hello
# 9

#PREDICTION: CORRECT

#9
pet_info = {
    "name": "Fido", 
    "age": 4, 
    "trick": "rolls over"
}
for key in pet_info:
    print(key)
    print(pet_info[key])

#PREDICTED OUTPUT:
# name
# Fido
# age
# 4
# trick
# rolls over 

#ACTUAL OUTPUT: 
    #in Terminal, in Python Tutor:
        # name
        # Fido
        # age
        # 4
        # trick
        # rolls over 
    #in VS Code:
        # trick
        # rolls over 
        # age
        # 4
        # name
        # Fido

#PREDICTION: CORRECT in Terminal and Python Tutor, INCORRECT in VS Code




#10
things_to_remember = {
    "First": "use the 20 minute rule and use the platform and other resources to find my answer",
    "Second": "ask my classmates for help, like how I would ask a fellow employee at my job",
    "Third": "ask an available TA in a public setting, so everyone can benefit from my question",
    "Fourth": "ask an available instructor"
}
for num, step in things_to_remember.items():
    print(num + ", I will " + step)

#PREDICTED OUTPUT:
# "First, I will use the 20 minute rule and use the platform and other resources to find my answer"
# "Second, I will ask my classmates for help, like how I would ask a fellow employee at my job"
# "Third, I will ask an available TA in a public setting, so everyone can benefit from my question"
# "Fourth, I will ask an available instructor"

#ACTUAL OUTPUT in VS Code:
# "Second, I will ask my classmates for help, like how I would ask a fellow employee at my job"
# "Fourth, I will ask an available instructor"
# "Third, I will ask an available TA in a public setting, so everyone can benefit from my question"
# "First, I will use the 20 minute rule and use the platform and other resources to find my answer"

#ACTUAL OUTPUT in Terminal, Python Tutor:
# "First, I will use the 20 minute rule and use the platform and other resources to find my answer"
# "Second, I will ask my classmates for help, like how I would ask a fellow employee at my job"
# "Third, I will ask an available TA in a public setting, so everyone can benefit from my question"
# "Fourth, I will ask an available instructor"

#PREDICTION: CORRECT in Terminal and Python Tutor, INCORRECT in VS Code