def cubes():
newlist=[]
number=[1,2,3,4,5,6,"seven"]
for i in number: if type(i)==int:
if i % 2==0:
newlist.append(i**3)
print(newlist)
cubes()
