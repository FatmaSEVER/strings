# strings

website = "http://www.fatmasever.com"
course = "Python Kursu: Baştan Sona Python Programlama Rehberiniz (40 saat)"

leng = len(course)
print(len(course))

print(website[7:10])

print(website[-3:])

print(course[0:15], '  and   ', course[-15:])  # course ifadesinin ilk 15 ve son 15 karakterini getirir.

print(course[::-1])  # course ifadesindeki karakterleri tersten yazar.

name, surname, age, job = 'Bora', 'Yılmaz', 32, 'engineer'

print(f'my name is {name} {surname}, my age is {age} and my job is {job}')

s = 'hello world'
s = s[:6] + 'W' + s[7:]
print(s)

#ya da

w = s.replace('w','W')
print(w)


f = 'abc   '*3
print(f)
