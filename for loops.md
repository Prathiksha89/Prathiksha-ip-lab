```python
numbers = ["1", "2", "3"]
for x in numbers:
  print(x)
```

    1
    2
    3
    


```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
```

    apple
    cherry
    


```python
down = 0
up = 100
for i in range(1,10):
    guessed_age = int((up + down) / 2)
    answer = input('Are you ' + str(guessed_age) + " years old?")
    if answer == 'correct':
        print("Nice")
        break
    elif answer == 'less':
        up = guessed_age
    elif answer == 'more':
        down = guessed_age
    else:
        print('wrong answer')
```

    Are you 50 years old?less
    Are you 25 years old?more
    Are you 37 years old?t
    wrong answer
    Are you 37 years old?correct
    Nice
    


```python
a = 33
b = 200
if b > a:
  print("b is greater than a")
```

    b is greater than a
    


```python
days=["sunday","monday","tuesday","wednesday","thursday","friday","saturday"]
for x in days:
  
    print(x)
```

    sunday
    monday
    tuesday
    wednesday
    thursday
    friday
    saturday
    


```python
weeks=['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday']

for x in weeks:
    if x=='Sunday':
     continue
    if x=='Monday':
     continue
    if x=='Tuesday':
     continue
    if x=='Saturday':
     continue
    print(x)

```

    Wednesday
    Thursday
    Friday
    


```python
weeks=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']

for x in weeks:
    if x=='Sunday':
     print('Sunday is holiday')
     continue
    if x=='Monday':
     print('No IP class in Monday')   
     continue
    if x=='Tuesday':
     print('No Python class in Tuesdayday')   
     continue
    if x=='Saturday':
     print('No AI class in Saturday')   
     continue
    print(x)
```

    No IP class in Monday
    No Python class in Tuesdayday
    Wednesday
    Thursday
    Friday
    No AI class in Saturday
    Sunday is holiday
    


```python

```
