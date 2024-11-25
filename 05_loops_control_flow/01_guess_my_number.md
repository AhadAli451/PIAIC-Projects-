# Statement 

It program work to number guessing

Like computer generate a number between 0 to 99 and you think like 50 so 50 number is higher or lower than computer number 


# Solution 

``` python
import random
random_generate_num: int = random.randint(1,20)

allow_attempt: int = 3
user_attempt: int = 0

    # 2 while condition
print("Wellcome To The Number Gussing Game  ")
while True:
      if user_attempt == allow_attempt:
        print("Your attempts is finsh so you may leave thankyou!")
        break
      try:
        print(f"attempts left: {allow_attempt - user_attempt}" )
        # 3 Get User Number
        user_input: int = int (input("Enter a number: "))
        user_attempt +=1


        if user_input == random_generate_num:
          print("Congrats! The number was:", random_generate_num)
          break
        elif user_input < random_generate_num:
          print("too low")
        elif user_input > random_generate_num:
          print("too high")
        else:
          print("correct")

      except ValueError:
            # Error handling if input is not a valid integer
            print("Invalid input! Please enter a number.")

```