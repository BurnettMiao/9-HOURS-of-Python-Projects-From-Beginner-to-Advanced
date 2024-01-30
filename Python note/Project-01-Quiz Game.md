## Project-01-Quiz Game

1. print()

```python
print('Welcome to my computer quiz!')
```

2. if else 判斷式，後面都須加上 :

```python
answer = input("What does CPU stand for? ")
if answer == "central processing unit":
  print('Correct!')
else:
  print('Incorrect!')
```

3. .lower() 轉成小寫

```python
playing = input('Do you want to play? ')

if playing.lower() != 'yes':
  quit()
```

或是這樣寫也行，緊接者 input()後面

```python
playing = input('Do you want to play? ').lower()

if playing != 'yes':
  quit()
```

4. .upper() 轉成大寫

```python
playing = input('Do you want to play? ')

if playing.upper() != 'yes':
  quit()
```

5. 把 number 轉成 string

```python
print('You got ' + str(score) + ' questions correct!')

print('You got ' + str((score / 4) * 100) + '%.')
```

6. quit() 為終止並跳出
