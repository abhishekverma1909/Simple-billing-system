# Simple-billing-system
cart=eval(input("Enter the price of you item:="))
for items in cart:
   if items>=500:
      print("Insurance is required for this",items,"items")
      continue
   print(items)
else:
   print("Thank you for shopping you item are processed")
