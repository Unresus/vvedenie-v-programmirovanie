a=[2,32,232,3123,14,3]
print('vot pervii massiv',a)
b=[45,7,67,65,786,435]
print('vot vtoroi massiv',b)
c=a
a=b
b=c
print('a vot oni v drygom poriadke',a,b)


m=[]
n=int(input('vvedite kolichestvo elementov massiva '))
for i in range(n):
    m.append(int(input()))
print(m)
B=[]
for i in range (n):
	B.append(sum(m[:i+1])/(i+1))
print(B)
    


m=[]
n=int(input('vvedite kolichestvo elementov massiva '))
for i in range(n):
    m.append(int(input()))
print(m)
m1=[]
d=0
for i in range (n):
	m1.append(m[i])
for i in range (n):
	if m[i]%2==1:
		m[i]+=d
		d=m1[i]		
print(m)




m=[]
n=int(input('vvedite kolichestvo elementov massiva '))
for i in range(n):
    m.append(int(input()))
print(m)
minn=m.index(min(m))
maxx=m.index(max(m))
for i in range (minn+1,maxx):
	m[i]=0
print(m)



m=[]
n=int(input('vvedite kolichestvo elementov massiva '))
for i in range(n):
    m.append(int(input()))
print(m)
m.sort()
print(m)
