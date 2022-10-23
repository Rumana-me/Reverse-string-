# Reverse-string-
Reverse string program using while loop in python 

 
def reverse(s): 
  reversed = "" 
  count = len(s) 
  while count > 0: 
    reversed += s[count - 1]   
    count = count - 1 
  return reversed 
 
s = input(" Enter the string") 
print(reverse(s))
