# Instruction

- To do the labs, you need to be able to get user's input. Python provides `input()` to do exactly that:
  ```
  >>> input()
  x
  'x'
  >>> input("This is a prompt")
  This is a promptAAAAA
  'AAAAA'
  >>> n = input("Give me some input: ")
  Give me some input: This is the input
  >>> n
  'This is the input'
  ```

- You also need a way to write to the console. Python provides `print()` to do exactly that:
  ```
  >>> print("Someething")
  Someething
  >>> x = 10
  >>> print(x)
  10
  >>> print(x, "+ 5 =", x + 5)
  10 + 5 = 15
  ```
# 1. Hello
Write a python script to ask for the current user’s name, and print out the following greeting:

> Tell me your name: `James Bond` <br />
> Hello `James Bond`! Nice to meet you

# 2. I can do math
Write a program to ask what year the current user was born, and print out the following message:

> What year were you born in? `2000` <br />
> You are `18` years old. You were/will be 30 years old in `2030`

# 3. May I have your cup cakes?
Write a program to ask the current user how many people are there in his/her family, then, prints out the following messages:

> How many people are there in your family? `4` <br />
> Congratulations! You have won the "Taming the Python" contest. <br />
> The grand prize is 103 up cakes <br />
> If you split them evenly among all `4` people in your family, <br />
> each person has `25` cup cakes. <br />
> ....May I keep the remaining `3` ...please?