De- 👋 Hi, I’m @BehcetAytimur
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
BehcetAytimur/BehcetAytimur is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---> 
x = lambda a: a + 10
print(x(5))

x = lambda a, b: a * b
print(x(5, 6))

x = lambda a, b, c: a + b + c
print(x(5, 6, 2))

def myfunc(n):
  return lambda a : a * n

mydoubler = myfunc(2)

print(mydoubler(11))

def myfunc(n):
  return lambda a : a * n

mytripler = myfunc(3)

print(mytripler(11))

def myfunc(n):
  return lambda a : a * n

mydoubler = myfunc(2)

print(mydoubler(11))

def myfunc(n):
  return lambda a : a * n

mydoubler = myfunc(2)
mytripler = myfunc(3)

print(mydoubler(11)) 
print(mytripler(11))

#Kisa bir süre için anonim bir işlev gerektiğinde lambda işlevlerini kullanmak gerekir.

#Lambda'nın gücü, onları başka bir işlevin içinde anonim bir işlev olarak kullandığınızda daha iyi gösterilir.

#Bir argüman alan bir fonksiyon tanımınız olduğunu ve bu argümanın bilinmeyen bir sayı ile çarpılacağını varsayalım, bu durumda lambda'nin gucu ortaya cikmaktadir.


