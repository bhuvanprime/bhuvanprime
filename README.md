
name = input("enter your name")
EID = input ("enter your employee ID")
deg = input ("enter your desgination")
basic =float(input("enter your basic salary"))
DA = basic*10/100
HRA = basic*15/100
PF = basic*12/100
gross = basic+DA+HRA+PF
net = basic-PF-HRA
print('''        ~~~~~~~~~~~~~~~~
        employee pay slip
        ~~~~~~~~~~~~~~~~~''')
print ("Name:",name)
print("Employee ID:",EID)
print("desgination:",deg)
print("salary information:",basic)
print("DA:",DA)
print("HRA:",HRA)
print("PF:",PF)
print ("gross salary:",gross)
print("net salay:",net)
