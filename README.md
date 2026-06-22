import time
import random

time.sleep(1)
print("this is 1xbet")
#or rubels
time.sleep(1)
print("bet price: 15$")

time.sleep(1)
print("you need to get 3 sevens")

#or randrage
time.sleep(3)
print("spining...")
time.sleep(3)
num1 = random.randint(1, 7)

time.sleep(3)
print("spining...")
time.sleep(3)
num2 = random.randint(1, 7)

time.sleep(3)
print("spining...")
time.sleep(3)
num3 = random.randint(1, 7)

seven_count = 0
if num1 == 7:
  seven_coount += 1
if num2 == 7:
  seven_count += 1
if num3 == 7:
  seven_count += 1

  print(f'| {num1} | {num2} | {num3} |')

if seven_count == 3
  print("you won 50$")
elif seven_count == 2
  print("you won 30$")
elif seven_count == 1
  print("you won 15$")
else:
  print("You haven't won anything")

print("the game is over if you want another dress for $15")




  
