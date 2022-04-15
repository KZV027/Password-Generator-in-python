# Password-Generator-in-python
import random
import string
def get_password(length):
  letter=string.ascii_lowercase #The lowercase letters 'abcdefghijklmnopqrstuvwxyz'
  result_str=''.join(random.choice(letter)
  for i in range(length))
  print("Password is:",length,"is",result_str)
get_password(10) #length of password
get_password(8) 
get_password(6) 
  
