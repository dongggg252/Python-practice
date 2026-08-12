import random
target = random.randint(1,99)
low, high = 1, 99
while True:
  guess = int(input(f"請猜一個數字({low}到{high}之間):"))
  if guess < target:
    print("太低了,繼續猜!")
    low = guess + 1
  elif guess > target:
    print("太高了,繼續猜!")
    high = guess - 1
  else:
    print(f"恭喜你,你猜對了,目標數字是 {target} ")
    break
