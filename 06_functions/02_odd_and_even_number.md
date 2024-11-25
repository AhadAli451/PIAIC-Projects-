# Statement 

It program only ask from user pour a any number and it program will tell you which number you are pour that number is odd or even 

Example :

What's a number 2 ?

that's a even number 

What's a number 3 ?

that's a odd number 

# Solution

``` python
def print_odd_num():
  for i in range(1, 99, 2):


   print_odd_num()


# prompt: i want to import even number 1 to 100 and all do print

def print_even_numbers():
  for i in range(2, 101, 2):


   print_even_numbers()


user_input = int(input("Enter a number: "))

if user_input % 2 == 0:
    print(f"{user_input} is an even number.")
else:
    print(f"{user_input} is an odd number.")
```