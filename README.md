# PositiveNums
# Python Program
# Python program to print positive Numbers in a List 

numlist = []
num = int(input("How many nos do u want:"))
for i in range(1,num+1):
    val=int(input("Enter the values %d:"%i))
    numlist.append(val)

print("\n Positive nos in the List are:")
for j in range(num):
    if(numlist[j] >=0):
        print(numlist[j], end = ' ')
