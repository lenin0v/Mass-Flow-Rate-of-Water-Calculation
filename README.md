# Mass-Flow-Rate-of-Water-Calculation
Intro to Thermal Sciences Schmidt Problem 7-7

#Finding mass flow rate of water (problem 7-7)

#oil
moil=float(input("Mass flow rate of oil:  "))
Cpoil=float(input("Heat capacity of oil:  "))
Tfoil=float(input("Final Temperature of oil:  "))
Tioil=float(input("Initial Temperature of oil:  "))

#water

Cpwater=float(input("Heat capacity of water:  "))
Tfwater=float(input("Final Temperature of water:  "))
Tiwater=float(input("Initial Temperature of water:  "))


#equation to get mass flow rate of water 

mwater = (-moil*(Cpoil)*(Tfoil-Tioil))/((Cpwater)*(Tfwater-Tiwater))

print  (f"mwater = {mwater}")
