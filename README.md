# Secret_Code
# This is a Python program to translate a message into a secret code language. 
import numpy as np
print("Welcome Agent Vinod")
import string
import random
import array as arr
 
# Initializing size of the string
N = 3
 
# using random.choices()
# generating random strings
res = ''.join(random.choices(string.ascii_lowercase +
                             string.digits, k=N))
Mess = input("Please enter the message you want to send to the RAW Headquaters\n")
a = list(Mess)
for i in range (0, 3):
    a[i], a[len(a)-i-1] = a[len(a)-i-1], a[i]
else:
     a = a.append(a[0])
     del a[0]
     a = append. random(3)
     a = add.start. random(3)

print("str(res)"+ a + str(res))
