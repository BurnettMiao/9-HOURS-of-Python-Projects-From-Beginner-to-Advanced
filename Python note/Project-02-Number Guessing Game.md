## Project-02-Number Guessing Game

1. import random 模組 (python 預設的模組)

```python
import random
```

2. 定義範圍 random.randrange(start, stop)，如下範例 (1, 10) 但不包含 10

```python
random.randrange(1, 10)
```

3. 定義範圍 random.randint(-5, 11)，如下範例 (1, 11) 包含 11

```python
random.randint(-5, 11)
```

4. isdigit() 字符串是否只由數字組成，然後轉成數字。int("25") -> 25 將 string 25 轉成 number 25

```python
top_of_range = input('Type a number: ')

if top_of_range.isdigit():
  top_of_range = int(top_of_range)
```

5. while loop 的使用

```python
while True:
  guesses += 1
  user_guess = input("Make a guess: ")
  if user_guess.isdigit():
    user_guess = int(user_guess)
  else:
    print('Please type a number next time.')
    continue

  if user_guess == random_number:
    print('You got it!')
    break
  elif user_guess > random_number:
    print('You were above the number!')
  else:
    print('You were below the number!')
```
