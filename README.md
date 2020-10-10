# Simple-billing-system
cart=[60,50,90,100,33,600,55,550,78,98,62,800,66,88]
for item in cart:
   if item>=500:
      print("To place this order insurance must be required")
      continue
   print("Your items are", item)
