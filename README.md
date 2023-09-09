# Tip_Calculator
#To calculate the contribution of each person on total bill, after including tip, and if they want to split among the present members

total_bill= input("what was the total bill?")
bill= int(total_bill)
percentage_tip= input("what percentage tip you like to give?")
Percentage_Tip= int(percentage_tip)
split= input("How many people to split the bill?")
splitting= int(split)
ind_contribution= (bill*(Percentage_Tip/100))
final_ind_contribution= bill+ind_contribution
print (f"Each person should pay {final_ind_contribution}")
