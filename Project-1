#The waiter choose the price that the coffee will be priced
coffeeprice1=float(input("How much will you charge for coffee? "))
cakeprice1=float(input("How much will you charge for cake "))
print("Coffee is " ,coffeeprice1)
print("Cake is ",cakeprice1)
choice=input("Would you like coffee or cake or both ")
#Stage 1 selection
if choice=="coffee":
  print("you chose coffee")
#stage 1a amount
  amountofcoffee=int(input("How many do you want? "))
#stage 1b total price 
  total=amountofcoffee*coffeeprice1
  print("Your total sums up to  £",total)
elif choice=="cake":
  print("You chose cake")
  #stage 1a amount
  amountofcake=int(input("How many do you want? "))
#stage 1b total price 
  total=amountofcake*cakeprice1
  print("Your total sums up to  £",total)
elif choice=="both":
  print("you chose both")
  #stage 1a amount
  amountofcoffee=int(input("How many cups of coffee do you want? "))
  amountofcake=int(input("How many plates of cake do you want? "))
#stage 1b total price 
  total=(amountofcoffee*coffeeprice1)+(amountofcake*cakeprice1)
  print("Your total sums up to  £",total)
else:
  print("Not a valid answer")
#stage 2a change
money=float(input("How much money do you have? "))
change=money-total
print ("Your change is £",change)
