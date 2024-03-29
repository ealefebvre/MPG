# MPG
# Miles Per Gallon Code
try:
    miles = float(input("How many miles"))
except:
    print ('bad miles input')
    exit ()
try:
    gallons = float(input("How many gallons"))
except:
    print ('Illegal input for gallons')
    exit ()

try:
    mpg = (miles/gallons)
except:
    print ('Cool, it must be an EV')
else:
    print ('miles per gallon is ',mpg)
