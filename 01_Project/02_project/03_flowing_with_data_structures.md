# problem statement

It program take a user input and add to in list but before list is empty but when 
user pour taxt or anyone word so it program to add in list 

+   **Like** 
   1. List before: []
   2. List after: ['Hello world!', 'Hello world!', 'Hello world!']

# Solution


``` python


  def add_things(my_list,work):
    for i in range(3):
      my_list.append(work)



  message =  input("what's your sentences")

  my_list =[]

  print("before list", my_list)
  add_things(my_list,message)
  print("after list", my_list)

  def test():


   test()
```