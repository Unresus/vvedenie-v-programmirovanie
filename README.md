import math
a=int(input('введите число секунд (целое) '))
b=a/60
c=int(b)
i=b-c
a=math.ceil(60*i)
print('убрав минутные отрезки, останетс ',a,' секунд')


a=int(input('vvedite kolichestvo dnei v promezhytke ot 1 do 365: '))
b=a/7
c=int(b)
i=b-c
a=math.ceil(7*i)
print(a)
if a==1:
    print('ponedelnik')
elif a==2:
    print('vtornik')
elif a==3:
    print('sreda')
elif a==4:
    print('chetverg')
elif a==5:
    print('piatnitsa')
elif a==6:
    print('sybbota')
else:
    print('voskresenie')


m=int(input('vvedite kolichestvo dnei v promezhytke ot 1 do 365: '))
o=int(input('vvedite nachalni den nedeli: '))
b=m%7
print(b)
a=b+o-1
if a==1:
    print('ponedelnik')
elif a==2:
    print('vtornik')
elif a==3:
    print('sreda')
elif a==4:
    print('chetverg')
elif a==5:
    print('piatnitsa')
elif a==6:
    print('sybbota')
else:
    print('voskresenie')




a=int(input('shirina priamoygolnika = '))
b=int(input('visota priamoygolnika = '))
c=int(input('razmer grani kyba = '))
o=a*b
i1=a/c
i11=int(i1)
i2=b/c
i22=int(i2)
i3=i22*i11
i33=a*b-i3*c*c
print('kolichestvo kvadratov = ',i3)
print('ostatok = ',i33)



a=int(input('vvedite god '))
b=a/100
b1=int(b)
b2=int(b+1)
print('eto ',b2,' vek')
