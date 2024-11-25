# Statement 

Basically it's a __International Voting Age program__ and it program ask age from user and this program make design like this program will ask **What's your Age** and then it will design it will see it user able to give vote *Any Three* countries 

__Country Voting Age__

+   Peturksbouipo_age: int = 16
+   Stanlau_age: int = 25
+   Mayengua_age: int = 48

# Solution

``` python
Peturksbouipo_age: int = 16
Stanlau_age: int = 25
Mayengua_age: int = 48

print("You can give vote to there countries")
user_age: int =  int(input("What's Your Age"))
if user_age == Peturksbouipo_age:
    print("You can give vote to Peturksbouipo",Peturksbouipo_age)
elif user_age > Peturksbouipo_age:
    print("You can't give vote to Peturksbouipo",Peturksbouipo_age)
if user_age == Stanlau_age:
      print("You can give vote to Stanlau",Stanlau_age)
elif user_age < Stanlau_age:
      print("You can't give vote to Stanlau",Stanlau_age)
if user_age == Mayengua_age:
      print("You can give vote to Mayengua",Mayengua_age)
elif user_age < Mayengua_age:
      print("You can't give vote to Mayengua",Mayengua_age)
else:
      print("You can't give vote to Mayengua",Mayengua_age)
```