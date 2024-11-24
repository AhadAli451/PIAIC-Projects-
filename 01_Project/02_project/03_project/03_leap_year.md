# problem statement 

It program tell that it is a leep year or that's not a leep year 

Here are solution!

# Solution

``` python
year = int(input("Please Enter a year: "))

if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 == 0:
            print("That's a leap year!")
        else:
            print("That's not a leap year.")
    else:
        print("That's a leap year!")
else:
    print("That's not a leap year.")
```
