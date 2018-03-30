# to-make-dictionary-of-cricket-players-with-their-scores
# to make dictionary for cricket players with their runs and display their the names of the players who played match 
dict={}
n=int(input("enter the no of  players , name pairs "))
for i in range(n):
    pname=input("enter the player's name : ")
    runs=int(input("enter the runs made by the player :"))
    dict.update({pname:runs})
print("the dictionary of cricket players with their runs : ",dict)
# total runs made by the team
print("total runs made by the players: ")
s=sum(dict.values())
print(s)
# display the names of the players 
print("\nthe names of the players are: ")
for j in dict.keys():
    print(j)
