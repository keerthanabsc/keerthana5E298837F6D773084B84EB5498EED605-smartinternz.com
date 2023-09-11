#implement a recursive function to calculate factroial of given number

def fact_rec(n):
 if n==0 or n==1:
  return 1
 else:
  return n*fact_rec(n-1)
  
number = 2
res = fact_rec(number)

print("The factroial of {} is {}.".format(number,res))