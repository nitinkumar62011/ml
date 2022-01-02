# Online Python compiler (interpreter) to run Python online.
# Write Python 3 code in this online editor and run it.
write the decimal to binary code
print("Hello world")
a=1600000000000
s=''
while True:
    if a%2==0:
        s=s+'0'
    else:
        s=s+'1'
    a=a>>1
    if a==0 or a==1:
        s=s+'1'
        break
print(s[::-1])
