#Customer Loan Eligibility Checker

Create a simple program that determines whether a customer is eligible for a loan based on their credit score and annual income. Use the following criteria:
If credit score is 750 or above and annual income is $50,000 or more, the customer is eligible for a premium loan.
If credit score is between 650 and 749 (inclusive) and annual income is $30,000 or more, the customer is eligible for a standard loan.
If credit score is below 650 or annual income is below $30,000, the customer is not eligible for a loan.¶

# datasciencebeginner

My data science beginner project
creditscore = float(input("Enter your credit score: "))
annualincome = float(input(" Enter you annual income: "))
if creditscore>=750:
    if annualincome>=50000:
        print("You are eligible for a premium loan")
    elif annualincome <50000:
        print("You are ineligible for a premium loan because your annual income is too low")
elif 650<=creditscore<=749:
    if annualincome>=30000:
        print("You are eligible for a standard loan")
    elif annualincome <50000:
        print("You are ineligible for a standard  loan because your annual income is too low")
elif creditscore<650:
    if annualincome<30000:
        print("You are not eligible for a standard loan")
    elif annualincome <50000:
        print("You are ineligible for a standard  loan because your annual income is too low")
else:
    print("You are ineligible for a loan") 
            
        
                            
                    
                
                    
