import math
a=int(input('введите значение угла в градусах '))
a=0.01*a/((180/math.pi)/100)
print('значение в радианах = ',a)


import math
a=int(input('введите значение угла в радианах '))
a=180/math.pi*a
print('значение в градусах = ',a)


x=int(input('введите массу конфет в кг '))
a=int(input(f"введите цену за {x} конфет "))
b=a/x
print('tsena 1 kg konfet',b)
y=int(input('теперь введите массу конфет в кг, чтобы узнать ее цену '))
print('tsena ravna ',y*b)

a=int(input('v1 = '))
b=int(input('v2 = '))
s=int(input('rasstoianie mezhdy nimi = '))
t=int(input('vremia = '))
s=(a+b)*t+s
print('rasstoianie mezhdy avtomobiliami = ',s)


print('введите данные для решения уравнения A * x + B = 0')
a=int(input('введите значение коэффициента A (коэффициент A не равен 0) '))
b=int(input('введите значение коэффициента B '))
x=-b/a
print('результат = ',x)

print('введите данные для решения системы линейных уравнений:')
print('A1·x + B1·y = C1')
print('A2·x + B2·y = C2')
a1=int(input('введите значение коэффициента A1 '))
b1=int(input('введите значение коэффициента B1 '))
a2=int(input('введите значение коэффициента A2 '))
b2=int(input('введите значение коэффициента B2 '))
c1=int(input('введите C1 '))
c2=int(input('введите C2 '))
y=(c1*a2-c2*a1)/(a2*b1-a1*b2)
if ((c1-b1*y)/a1) == ((c2-b2*y)/a2):
    x=(c1-b1*y)/a1
    print('X = ',x,'Y = ',y)


