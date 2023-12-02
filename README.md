# health-check
#To find the health condition of patient using function
def health():
    if conscious == "yes":
        print("good condition")
    elif conscious == "no" :
        print("critical condition")
    else:
        print("Please enter yes or no")
conscious = input("Enter the conscious state of patient(yes/no):")
health()
