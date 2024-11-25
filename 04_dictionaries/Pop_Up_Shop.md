# Statement 

It tell us total cost of furites 

How Many do you want to buy furites?:

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