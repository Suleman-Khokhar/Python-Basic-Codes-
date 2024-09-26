# Question 01
'''Problem Description
February 18 is a special date for the CCC this year.
Write a program that asks the user for a numerical month and numerical day of the month and then
determines whether that date occurs before, after, or on February 18.
If the date occurs before February 18, output the word Before. If the date occurs after February
18, output the word After. If the date is February 18, output the word Special.'''
     #Month and date 
month=int(input("Enter the month:"))
date=int(input("Enter the date:"))
if(month==2):
    if(date==18):
        print("Speacial ")
    elif(date>18):
        print("After")
    else:
        print("Before")
elif(month>2):
    print("After")
else:
    print("Before")                   
# Question 02
'''Problem Description
Each player in a tournament plays six games. There are no ties. The tournament director places
the players in groups based on the results of games as follows:
• if a player wins 5 or 6 games, they are placed in Group 1;
• if a player wins 3 or 4 games, they are placed in Group 2;
• if a player wins 1 or 2 games, they are placed in Group 3;
• if a player does not win any games, they are eliminated from the tournament.'''
#Tournament Selection
result1=str(input("Enter the result of first game : "))
result2=str(input("Enter the result of second game : "))
result3=str(input("Enter the result of third game : "))
result4=str(input("Enter the result of forth game : "))
result5=str(input("Enter the result of fifth game : "))
result6=str(input("Enter the result of sixth game : "))
result = result1+result2+result3+result4+result5+result6
results=result.count("w")
if (results == 5) or (results == 6):
    print("Grou 1")
elif (results == 3) or (results == 4) :
    print("Group 2")
elif (results == 1) or (results == 2) :
    print("Group 3")
else :
    print(" eliminated from the tournament ")
    
