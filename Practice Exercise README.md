# Python-Exercise-2
Python program to display all the prime numbers within an interval

# change the values of lower and upper for a different result
lower = 900
upper = 1000

# uncomment the following lines to take input from the user
#lower = int(input("Enter lower range: "))
#upper = int(input("Enter upper range: "))

print("Prime numbers between",lower,"and",upper,"are:")

for num in range(lower,upper + 1):
   # prime numbers are greater than 1
   if num > 1:
       for i in range(2,num): --Please explain
           if (num % i) == 0:  
               break
       else:
           print(num)



Enter and execute the following code:
name=input("what is your name: ")
for x in range(5):
    for x in range(3):
        print(name+" ",end=" ")
    print()
   a.  What does the program display?
   b. How many FOR loops are in this code? _______  Is one loop completely executed before the next loop begins?   _______   What do you call this type of loop?_____
   c.  How many times is the following line of code executed in the program?
 print(name+" ",end=" ")
   d.  Label the inner loop and the outer loop.
   e.  What does the inner loop do?
   f.  What does the outer loop do?
2. If  you were asked to create a Python program that displayed the adjacent rectangle, you could easily do it with a set of print statements. You can also create it with a FOR loop and a print statement. This exercise will go through the steps to create a program that will print similar output but allows the user to determine the length and width of the figure when they execute the program.
 


x = int(input("What is your grade?"))
def grade(x):

if x >= 90:
        return "A"
    else:
        if x >= 80:
            return "B"
        else:
            if x >= 70:
                return "C"
            else:
                if x >= 60:
                    return "D"
                else:
                    return "F"

print( "Grade:", grade(x))

