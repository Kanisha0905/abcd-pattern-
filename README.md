# abcd-pattern-
s = input("Enter the String: ")
n = len(s)
for i in range(1, n+1):
    for j in range(i):
        print(s[j], end='')
    print("")
output:
Enter the String: Computer
C
Co
Com
Comp
Compu
Comput
Compute
Computer

