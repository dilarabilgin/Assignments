num = (input("Please enter a positive number :"))

if not num.isnumeric() :
  num = (input("It is an invalid entry. Don't use non-numeric, float, or negative values! Enter another number: "))

exponent = len(str(num)) #n-digits
digits = list(map(int, num)) #list of digits map() birbirinden ayiriyor rakamlari
exp_dig = [] # empty list of digits**exponent

for n in digits:
  exp_dig.append(n**exponent) # digits**exponent add to empty list

sumofnumbers = sum(exp_dig)
if str(sumofnumbers) == num :
  print(num +  " is an Armstrong number.")
else :
  print(num + " is not an Armstrong number.")
