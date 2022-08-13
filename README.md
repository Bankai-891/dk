print("Enter your name:")
name =input()
print("Which year did you born:")
year =int(input())

if year>2006:
    print("I am your big bro!!")
elif year==2006:
    print("You can be my freind.")
    
else:
    print("You can be my idiol")
print("Enter 4 for male and 8 for female:\n")
print("gender")     
op = int(input())

if op < 5:
    print("Male")
else:
     print("Female")
 
print("Enter your age:")
age =int(input())
if age<18:
    print("Sorry!, But you are not aligiable for drive.")
elif age==18:
    print("You have to give a test.")
else :
    print("You can dive, But dirve carefully!") 
    
    print("Thanks for giving your time :)")   
