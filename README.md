# Simple-billing-system
cart=eval(input("Enter the price of your item:="))
for item in cart:
   if item>=500:
      print("To place this order insurance must be required")
      continue
   print("Your items are", item)
