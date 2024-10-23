# Bill-Split-calculator


a=int(input("What is the total amount (in Rs.): "))
b=int(input("What is the tip amount you want to give (in %): "))
c=int(input("In how many people you want to split the amount: "))
d=a*b/100
a+=d
e=a/c
print(f"Each person have to pay Rs.{e}")
