# assignment-3
#To Calculate the length of transition curve
V= int(input("Enter the value of design speed: "))
R= int(input("Enter the value of Radius of curvature: ")
N= int(input("Enter the value of slope: "))
W= float(input("Enter the value of width of road including extra widening: ")
emax=float(input("'enter the value for plain terain:"))
ecal= (V*V/(225*R))
print("The value of Super elevation:",ecal) if ecal<emax:
print(ecal) else:
print(emax) Ls=(emax*N*W/2)
print("The length of transition curve:", Ls)
