# Python
```python
import random as ra
def game():
    num = ra.randrange(1,100)
    max = 100
    min = 1
    print(num)
    value = input()
    value = int(value)
    while value != num:
        if value > num:
            max = value
            print('{0} to {1}'.format(min,max))
            value = int(input())
        elif num > value:
            min = value
            print('{0} to {1}'.format(min,max))
            value = int(input())
    print('u are god damn right')

if __name__ == '__main__':
    game()
```