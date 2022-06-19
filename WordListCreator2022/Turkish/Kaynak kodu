import itertools as t
chars = input("Information About the Victim :")
min = int(input("Enter Number About Victim At Least :"))
max = int(input("Enter Number About Victim Maximum :"))
output = input("File name :")

if output == "" or output is None:
    file = open(chars+".txt",'w')
else:
    file = open(output,'w')
if min == max:
    for i in range(min, max + 1):
        for a in t.product(chars, repeat= i):
            s = "".join(a)
            file.write(s+"\n")
        file.close()

elif min < max:
    for i in range(min, max + 1):
        for a in t.product(chars, repeat= i):
            s = "".join(a)
            file.write(s+"\n")
        file.close()
else:
    print("Maximum reps must be greater than minimum reps")
    exit
if output == "" or output is None:
    print("Saved the file by name:"+chars+".txt")
else:
    print("Saved the file by name :"+output)
