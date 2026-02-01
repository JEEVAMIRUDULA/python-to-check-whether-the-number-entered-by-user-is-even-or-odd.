# python-to-check-whether-the-number-entered-by-user-is-even-or-odd.
num=int(input("Enter any number:"))
flag=num%2
if flag==0:
    print(num,"is an even number")
elif flag==1:
    print(num,"is an odd number")
else:
   print("Error,Invalid input")

Output;
Enter any number:89
89 is an odd number

