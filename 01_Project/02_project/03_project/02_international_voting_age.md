# problem statement 

Write a program which asks a user for their age and lets them know if they can or can't vote in the following three fictional countries.

Around the world, different countries have different voting ages. In the fictional countries of Peturksbouipo, Stanlau, and Mayengua, the voting ages are very different:

the voting age in Peturksbouipo is 16 (in real life, this is the voting age in, for example, Scotland, Ethiopia, and Austria)

the voting age in Stanlau is 25 (in real life this is the voting age in the United Arab Emirates)

the voting age in Mayengua is 48 (in real life, as far as we can tell, this isn't the voting age anywhere)

Your code should prompt the for their age and print whether or not they can vote in Peturksbouipo, Stanlau, or Mayengua.

Here's a sample run of the program (user input is in blue):

How old are you? 20 You can vote in Peturksbouipo where the voting age is 16. You cannot vote in Stanlau where the voting age is 25. You cannot vote in Mayengua where the voting age is 48.

Here are solution!

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