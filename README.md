# code
addition of digits placed in ones position of a number
l=[] #intializing empty lists 
s=[]
n1=input() #taking input in the form of strings
n2=input()
for i in n1:     #appending the values into the lists
    l.append(i)
for i in n2:
    s.append(i)
l1=len(l)        #finding length of lists
s1=len(s)
l2=int(l[l1-1])    #finding the last digit using indexing and converting it into integer type
s2=int(s[s1-1])
sum1=l2+s2         #adding the last digits
print(sum1)
