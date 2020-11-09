# Palindrome-checker
# This code takes input from the user and checks if the number entered is a palindrome or not. If the number is a palindrome, it displays the result after reversing the number and displays, "the number is a palindrome". If the number is not a palindrome, it will display "The number is not a palindrome".

num1 = int(input("Please enter a number: "))
temp = num1
rev = 0
while num1>0:
     rem = num1 % 10
     rev = (rev*10) + rem
     num1 = num1//10
print (rev)
if temp == rev:
   print("The number is a palindrome")
else:
    print("The number is not a palindrome")
print("Loop over!!")
