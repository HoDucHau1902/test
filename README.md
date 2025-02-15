import string
name="Ho Duc Hau"
key=24
a=list(string.ascii_lowercase)  
b=a[key:]+a[:key]
print("Ten duoc ma hoa: ",end='')
for i in name:
    if i in a:
        print(b[a.index(i)],end='')
    else:
        print(i,end="")
