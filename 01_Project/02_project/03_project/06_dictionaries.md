 # problem statement

Basically It program tell you total cost of furites like it program ask from you how may do you want to furites and ask and ask until they finished their furite list 

Here are solution!

# Solution 

``` python
 furites = {"apple": 1.3 ,"banana": 1.1 ,"orange": 3.0, "mango": 1.0, "pinapple": 1.5}

total_cost: int = 0

for furite_name in furites:
    price = furites[furite_name]
    Boughet_amount = int(input("How Many(" + furite_name + ") do you want to buy?: "))
    total_cost += (price * Boughet_amount)

    print("Your total is $" + str(total_cost))
```