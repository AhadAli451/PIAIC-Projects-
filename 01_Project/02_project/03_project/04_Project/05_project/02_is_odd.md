# Problem statement 

It program user pour input and it program tell him it is even number is or it is odd number 

+   like the number is 2 

+   2 the number is even number

+   like the number is 3

+   3 the number is odd number 

# Solution
```python
def print_odd_num():
  for i in range(1, 99, 2):


   print_odd_num()



def print_even_numbers():
  for i in range(2, 101, 2):


   print_even_numbers()


user_input = int(input("Enter a number: "))

if user_input % 2 == 0:
    print(f"{user_input} is an even number.")
else:
    print(f"{user_input} is an odd number.")
```    
