# Password-Generator-in-python-
import random
import string

len=int(input("enter the lenght of the password"))

upper = string.ascii_uppercase
lower = string.ascii_lowercase
num = string.digits
symbols = string.punctuation

all=upper+lower+num+symbols

temp = random.sample(all,len)
password = "".join(temp)
print(password)
