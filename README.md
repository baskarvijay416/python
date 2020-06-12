# python
coding
def compound_interest(principle, rate, time): 
  
    # Calculates compound interest  
    CI = principle * (pow((1 + rate / 100), time)) 
    print("Compound interest is", CI) 
  
# Driver Code  
compound_interest(10000, 10.25, 5) 
ut sale amount 
amt = int(input("Enter Sale Amount: "))

# conditions to check amount and get discount
if(amt>0):
    if amt<=5000:
       disc = amt*0.05
    else:
        if amt<=15000:
            disc=amt*0.12
        else:
            if amt<=25000:
                disc=0.2 * amt
            else:
                disc=0.3 * amt
    
     discount and net payable amount 
    print("Discount : ",disc)
    print("Net Pay  : ",amt-disc)
else:
    print("Invalid Amount")
