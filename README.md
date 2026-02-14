# Posting-my-1st-python-mini-project
Mini Login System Using Python
while True:
    username=input("Enter Your UserName : ")
    if username=="Admin":
        
    
        while True:
         password=input("Enter your PassWord : ")
        
         if password=="12345678":
            print("Login Successfull")
            break
         else:
            print("Wrong Password, Try again")
        break
        

    else:
        print("Wrong Username, Try Again")
