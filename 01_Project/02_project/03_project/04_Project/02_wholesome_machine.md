# Problem statement 

Basically it program ask you affirmation 

__Example__
Please type the following affirmation: I am capable of doing anything I put my mind to. Hmmm That was not the affirmation. Please type the following affirmation: I am capable of doing anything I put my mind to. I am capable of doing anything I put my mind to. That's right! :

Note that you can call input() with no prompt and it will still wait for a user to type something!

# Solution 
```python
affirmation: str = "I am capable of doing anything I put my mind to."

while True:
   user_feedback = input("Please type the following affirmation:" + affirmation)
   if user_feedback == affirmation:
    print("That was the affirmation. Thank you!")
    break
   else:
    print("Hmmm That was not the affirmation. Please type the following affirmation: ")
```