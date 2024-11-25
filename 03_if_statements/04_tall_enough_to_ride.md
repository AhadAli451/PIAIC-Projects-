# Statement 

It program help and ask you your tall and it give you permission that you able to ride 

Minimum height is 8 feet 
Minimum height is 5 feet

How tall are you ? 7 feet 

So you can ride 

How tall are you ? 4

So you can't ride 

Basically it just this work 


# Solution

``` python

print("Requriment For Ride!")
print("Maximun Height is 8 feet")
print("Minimum Height is 5 feet")

user_height: int =int(input("Enter Your Height"))
if user_height == 8:
    print("You can ride")
elif user_height == 6:
    print("You can ride")
elif user_height < 5:
    print("You can't ride")
``` 