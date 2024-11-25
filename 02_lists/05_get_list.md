# Statement 

It a program which continuously asks the user to enter values which are added one by one into a list. When the user presses enter without typing anything, print the list.

Here's a sample run (user input is in blue):

Enter a value: 1 Enter a value: 2 Enter a value: 3 Enter a value: Here's the list: ['1', '2', '3']

# Solution 

``` python
add_list = []

while True:
 user_input = (input("Enter A Value"))
 add_list.append(user_input)
 print("here a list", add_list)
 break
```
