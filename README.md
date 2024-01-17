import random
roop = "abcefghijklmnopqrstwxyz0123456789ABCDEFGHIJKLMNOPQRSTWXYZ@&*$%#"
lenght=int(input("enter your password lenght: "))
pasword=""
for a in range(lenght):
  pasword+=random.choice(roop)
print(pasword)
