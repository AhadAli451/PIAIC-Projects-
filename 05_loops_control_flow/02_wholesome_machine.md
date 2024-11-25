# Statement 

It is a simple program just take input affirmation


# Solution

``` python
affirmation: str = "I am capable of doing anything I put my mind to."

while True:
   user_feedback = input("Please type the following affirmation:" + affirmation)
   if user_feedback == affirmation:
    print("That was the affirmation. Thank you!")
    break
   else:
    print("Hmmm That was not the affirmation. Please type the following affirmation: ")
```