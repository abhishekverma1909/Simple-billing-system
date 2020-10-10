# Simple-billing-system
cart=eval(input("Enter the price of you item:="))
for item in cart:
   if item>=500:
      print("Insurance is required for this",item,"item")
      continue
   print(item)
else:
   print("Thank you for shopping you items are processed")
