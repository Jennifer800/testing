# testing
#The variable nested contains a nested list. Assign ‘snake’ to the variable output using indexing.

nested = [['dog', 'cat', 'horse'], ['frog', 'turtle', 'snake', 'gecko'], ['hamster', 'gerbil', 'rat', 'ferret']]
output = nested[1][2]

#Provided is a nested data structure. Follow the instructions in the comments below. Do not hard code.

nested = {'data': ['finding', 23, ['exercises', 'hangout', 34]], 'window': ['part', 'whole', [], 'sum', ['math', 'calculus', 'algebra', 'geometry', 'statistics',['physics', 'chemistry', 'biology']]]}

# Check to see if the string data is a key in nested, if it is, assign True to the variable data, otherwise assign False.
for key in nested:
    if 'data' in key:
        data = True
    else:
        False
    
# Check to see if the integer 24 is in the value of the key data, if it is then assign to the variable twentyfour the value of True, otherwise False.
for val in nested.items():
    if 24 in val:
        twentyfour = True
    else:
        twentyfour = False
# Check to see that the string 'whole' is not in the value of the key window. If it's not, then assign to the variable whole the value of True, otherwise False.

for val in nested:
    if 'whole' in val[3]:
        whole = True
    else:
         whole = False

# Check to see if the string 'physics' is a key in the dictionary nested. If it is, assign to the variable physics, the value of True, otherwise False.
for key in nested:
    if 'physics' in key:
        
        physics = True
    else:
        physics = False

#The variable nested_d contains a nested dictionary with the gold medal counts for the top four countries in the past three Olympics. Assign the value of Great Britain’s gold medal count from the London Olympics to the variable london_gold.
#Use indexing. Do not hardcode.

nested_d = {'Beijing':{'China':51, 'USA':36, 'Russia':22, 'Great Britain':19}, 'London':{'USA':46, 'China':38, 'Great Britain':29, 'Russia':22}, 'Rio':{'USA':35, 'Great Britain':22, 'China':20, 'Germany':13}}
london_gold = nested_d["London"]["Great Britain"]

#Below, we have provided a nested dictionary. Index into the dictionary to create variables that we have listed in the ActiveCode window.


sports = {'swimming': ['butterfly', 'breaststroke', 'backstroke', 'freestyle'], 'diving': ['springboard', 'platform', 'synchronized'], 'track': ['sprint', 'distance', 'jumps', 'throws'], 'gymnastics': {'women':['vault', 'floor', 'uneven bars', 'balance beam'], 'men': ['vault', 'parallel bars', 'floor', 'rings']}}

# Assign the string 'backstroke' to the name v1
v1 = sports['swimming'][2]

# Assign the string 'platform' to the name v2
v2 = sports['diving'][1]

# Assign the list ['vault', 'floor', 'uneven bars', 'balance beam'] to the name v3
v3 = sports['gymnastics']['women'][:]
# Assign the string 'rings' to the name v4
v4 = sports['gymnastics']['men'][3]

#Given the dictionary, nested_d, save the medal count for the USA from all three Olympics in the dictionary to the list US_count.

nested_d = {'Beijing':{'China':51, 'USA':36, 'Russia':22, 'Great Britain':19}, 'London':{'USA':46, 'China':38, 'Great Britain':29, 'Russia':22}, 'Rio':{'USA':35, 'Great Britain':22, 'China':20, 'Germany':13}}

US_count = []
for val in nested_d:
    US_count.append(nested_d[val]["USA"])
            
   
   #Iterate through the contents of l_of_l and assign the third element of sublist to a new list called third.


l_of_l = [['purple', 'mauve', 'blue'], ['red', 'maroon', 'blood orange', 'crimson'], ['sea green', 'cornflower', 'lavender', 'indigo'], ['yellow', 'amarillo', 'mac n cheese', 'golden rod']]
third = []
for i in l_of_l:
    third.append(i[2])
    
 #Given below is a list of lists of athletes. Create a list, t, that saves only the athlete’s name if it contains the letter “t”. If it does not contain the letter “t”, save the athlete name into list other.

athletes = [['Phelps', 'Lochte', 'Schooling', 'Ledecky', 'Franklin'], ['Felix', 'Bolt', 'Gardner', 'Eaton'], ['Biles', 'Douglas', 'Hamm', 'Raisman', 'Mikulak', 'Dalton']]
t = []
other = []
for name in athletes:
    for x in name:
        if 't' in x:
            t.append(x)
        elif 't' not in x:
            other.append(x)
    
    
