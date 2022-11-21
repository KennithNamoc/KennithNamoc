print ("WELCOME TO OUR PROGRAM RANKING SYSTEM FOR 1ST SEMESTER ")

name = input("\nEnter your name : ")
section = input("Enter your section : ")

print("\nPlease put your grades in every subject.")

sub1 = int(input("\nEthics : "))
sub2 = int(input("Understanding the Self : "))
sub3 = int(input("Mathematics in the Modern World : "))
sub4 = int(input("Computer Programming 1 : "))

sum = sub1 + sub2 + sub3 + sub4
average = sum / 4

print("\nName :",name)
print("Section : ",section)
print("Average : ",average)


if  average >=50:
    if average >= 96 and 96 <=100:
        print("\n",name, "YOU ARE THE TOP 1 WITH AN AVERAGE OF", average , "AND HAVE BEEN PROMOTED TO SECOND SEMESTER! CONGRATULATIONS!")
    elif average >= 91 and 91 <= 95:
        print("\n",name, "YOU ARE THE TOP 2 WITH AN AVERAGE OF", average, "AND HAVE BEEN PROMOTED TO SECOND SEMESTER! CONGRATULATIONS!")
    elif average >= 85 and 85 <= 90:
        print("\n",name, "YOU ARE THE TOP 3 WITH AN AVERAGE OF", average, "AND HAVE BEEN PROMOTED TO SECOND SEMESTER! CONGRATULATIONS!")
    elif average >= 50 and 50 <= 85:
        print("\n",name, "YOU PASSED THIS SEMESTER. CONGRATULATIONS!")    
    else:
        print("\nYOU FAILED!")
else:
    print("\nSORRY", name, "YOU FAILED IN THIS 1ST SEMESTER !")
