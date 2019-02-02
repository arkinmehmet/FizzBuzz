FizzBuzz

How to write any words besides numbers. FizzBuzz sample below:

for number in range (1,101):

    a = ''
    
    if number % 3 == 0:
    
        a += "Fizz"
        
    if number % 5 == 0:
    
        a += "Buzz"
        
    if a == '' :
    
        a = number
        
    print (a)
