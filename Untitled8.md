```python
# Write a for loop that prints out all the element between -5 and 5 using the range function.

for i in range(-4,5):
    print(i)

```

    -4
    -3
    -2
    -1
    0
    1
    2
    3
    4



```python
# Print the elements of the following list: Genres=[ 'rock', 'R&B', 'Soundtrack', 'R&B', 'soul', 'pop'] Make sure you follow Python conventions.
Genres=[ 'rock', 'R&B', 'Soundtrack', 'R&B', 'soul', 'pop']
for c in Genres:
        print(c)

print(c)
```

    rock
    R&B
    Soundtrack
    R&B
    soul
    pop
    pop



```python
# Write a for loop that prints out the following list: squares=['red', 'yellow', 'green', 'purple', 'blue']
squares=['red', 'yellow', 'green', 'purple', 'blue']
for squire in squares:
    print(squire)
```

    red
    yellow
    green
    purple
    blue



```python
# while loop to display the values of the Rating of an album playlist stored in the list PlayListRatings. If the score is less than 6, exit the loop.
PlayListRatings = [10, 9.5, 10, 8, 7.5, 5, 10, 10]
i=0
ratings = PlayListRatings[0]

while (i< len(PlayListRatings) and ratings >=6):
    ratings = PlayListRatings[i]
    print(ratings)

    i=i+1
```

    10
    9.5
    10
    8
    7.5
    5



```python
squares = ['orange', 'orange', 'purple', 'blue ', 'orange']
new_squares = []
i = 0
while(i < len(squares) and squares[i] == 'orange'):
    new_squares.append(squares[i])
    i = i + 1
print (new_squares)
```

    ['orange', 'orange']



```python

```
