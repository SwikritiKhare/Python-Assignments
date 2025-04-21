# Python-Assignments 
# Question 1:#Create a variable x with the value 15 . Perform floored division by 4 and
#print the result. What is the difference between floored division and normal
#division?

    x = 15
result = x // 4
print("Floored Division Result:", result)
     
     Floored Division Result: 3

#2. Question 2:Write a program to calculate 8 ** 2 and 16 ** 0.5 . Print both results and  describe what each represents

x=8
y=16
result= x**2
print("8 raise to power 2:",result)
result=y**0.5
print ("16 raise to power 0.5:",result)


    8 raise to power 2: 64
    16 raise to power 0.5: 4.0


#3. Question 3:Use arithmetic operators to solve the following expression: 20 - 5 * 3 + 8 /4 .
#Use parentheses to make sure the addition happens before multiplication. Print the output.

print(20-5*3+8/4)

    7.0



[ ]#4. Question 4:Assign the value 7 to a variable num . Convert it to a float and print the result. What is the difference between 7 and 7.0 ?

x=7
print (x)
type(x)
         
    7
    int

[ ] num = 7
   float_num = float(num)
   print("Converted to float:", float_num)

    Converted to float: 7.0

[ ] #5. Question 5:#Use a comparison operator to check if 100 is greater than 50 . Print the result and indicate what type of value this is.
 
  result= 100>50
print("Is 100 greater than 50=",result)
print ("type of result", type(result))

    Is 100 greater than 50= True
    type of result <class 'bool'>

[ ] #Question 6: Assign True to a variable is_sunny and False to is_weekend . Use logical operators to check if it is sunny and the weekend ( is_sunny and is_weekend ).#Print the result.

is_sunny = True
is_weekend = False
result = is_sunny and is_weekend
print(result)

    False

[ ] from types import prepare_class
#7 Create a variable password and set it to "my_password123" . Ask the user to input a password and print True if the input matches the value of password ,
#otherwise print False .

password= input("enter password=")
if password == ("my_password123"):
  print("true")
else:
  print("false")
        
    enter password=my_password123
    true

[ ] #8 Assign the value 50 to a variable marks . Increment the value of marks by 5
#using the += operator, then print the new value.

marks= 50



[ ] marks


    50

[ ] marks += 5

[ ] marks
 
    55

[ ] i=[5]
for i in range(3):
    print (i*i)

    0
    1
    4






