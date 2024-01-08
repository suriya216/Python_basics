Problem on Variable
The problem is about to find a person have age to vote and he is a new voter.
name = 'Karthi'
age = 20
is_new = True
if is_new and age >= 18:
    print ('He can vote!')
else:
    print ("He can't vote!")

- Here **is_new** is a *boolean* variable which can hold only **“True”** and **“False”** as value. Technically it holds binary value of 0 and 1.
- In else part inside the print statement, I needed to use double quotation marks **(”...“).** Because inside the print statement I use single **apostrophe  ‘  .** The python interpreter gets confuses.
