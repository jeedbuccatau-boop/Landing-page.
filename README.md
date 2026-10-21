
print("========================================")
print("       FARE COMPUTATION SYSTEM")
print("========================================")
print()
print("          Welcome, Passenger!")
print("    Your ride, your fare, made simple.")
print()
print("-------------- MAIN MENU --------------")
print("[1] Calculate Fare")
print("[2] About")
print("[3] Exit")
print()

choice = input("Enter your choice: ")

if choice == "1":
    import fare_computation

elif choice == "2":
    print()
    print("--------------- ABOUT ---------------")
    print("This program calculates the estimated")
    print("tricycle fare based on distance and")
    print("passenger type.")

elif choice == "3":
    print()
    print("Thank you for using our Fare Computation System!")
    print("We appreciate your trust.")
    print("Have a safe and pleasant trip!")
    exit()

else:
    print("Invalid choice. Please try again.")
    
