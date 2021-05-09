# BMI-Calculator
it's a BMI CalculatorMass = float ( input ("Enter your mass in kilograms "))

Height = float ( input ("Enter your height in metres "))

def calculate (M,H):

    return M / (H ** 2)

BMI = float( calculate (Mass, Height))

def find_person_standard (BMI):

    if BMI < 18.5:
        return "You're Under Weight, just like me!"

    if BMI < 25 :
        return "You're fine! nothing to worry about! Your Acceptable Weight"

    if BMI < 30:
        return "You're Over Weight"

    if BMI > 30:
        return "You're Obese"

Results = find_person_standard(BMI)

print (Results)

Yes = input ("Do you want to know your exact BMI? (Y/N) ")

if Yes == "Y" or "y":
    print("This is your BMI: ")
    print(BMI)
    print("Good Bye!")
else:
    print ("Good Bye then!")

