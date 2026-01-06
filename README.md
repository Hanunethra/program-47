# program-47
c=0
p=1.0
count=int(input("enter the number of values:"))
while(c<count):
x=float(input("enter a real number:"))
c=c+1
p=p*x
gm=pow(p,1.0/count)
print("the geometric mean is:",gm)
Output:

enter the number of values:5
enter a real number:2
enter a real number:6
enter a real number:9
enter a real number:8
enter a real number:5
the geometric mean is: 5.3345372167932
