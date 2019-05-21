# 猜数字

```python
import random
guess = random.randint(1, 100)

print('')
print('Guess the number')
print("Computer: There's a number between 1 and 100 in my mind, can you guess it?")
print('')

while True:
  eric = input("Please input your guess: ")
  # convert eric to int
  eric = int(eric)
  if eric == gues:
    print("You got it!")
    break
  elif eric < guess:
    print("too small")
  else:
    print("too big")

```



