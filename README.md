# tip_calculator
Helps you to calculate tip at any purchase

#If the bill was $150.00, split between 5 people, with 12% tip. 

#Each person should pay (150.00 / 5) * 1.12 = 33.6
#Format the result to 2 decimal places = 33.60

#Tip: There are 2 ways to round a number. You might have to do some Googling to solve this.💪

#Write your code below this line 👇
print("Welcome to the tip calculator.")
bill=float(input("what was the total bill? "))
percent=int(input("What percentage tip would you like to give? 10, 12,or 15? "))
people=int(input("how many people to split the bill? "))
s=float((bill/people)*(1+(percent/100)))
result = round(s,2)
r="{:.2f}".format(result)
print(f"Each person should pay: ${r}")
