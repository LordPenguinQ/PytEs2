1. x = "\\\\"
print(len(x))
-will print 2
2. import os
os.mkdir('pictures')
os.chdir('pictures')
print(os.getcwd())
-Operating system name
-Hardware identifier
3. assert var != 0
-will stop the program when var == 0
4. class A:
    A = 1
    def __init__(self):
       self.a = 0
print(hasattr(A, 'a'))
-False
5. from datetime import timedelta
delta = timedelta(weeks = 1, days = 7, hours = 11)
print(delta * 2)
-28 days, 22:00:00
6. class A:
    def __init__(self, v=2)
    def set(self, v=1):
       self.v +=v
       return self.v
a = A()
b = a
b.set()
print(a.v)
-3
7. class A:
   def __init__(self, v):
      self.__a = v + 1
a = A(0)
print(a.__a)
-The code will raise an AttributeError except
8. Knowing that a function named fun() resides in a module named mod , and was imported using the following statement:
from mod import fun
choose the right to invoke the fun() function:
-fun()
9. What output will appear after running the following snippet?
-A list of all the entities residing in the math module
10. import random

 Insert lines of code here.

print(a, b, 
6 82 0
-	a = random.randint(0, 100)
	b = random.randrange(10, 100, 3)
	c = random.choice((0, 100, 3))
11. from datetime import datetime
datetime_1 = datetime(2019, 11, 27, 11, 27, 22)
datetime_2 = datetime(2019, 11, 27, 0, 0, 0)
print(datetime_1 - datetime_2)
-11:27:22
12. import calendar
calendar.setfirstweekday(calendar.SUNDAY)
print(calendar.weekheader(3))
-Sun Mon Tue Wed Thu Fri Sat
13. class A: 
-The code will print b
14. numbers  [0, 2, 7, 9, 10]
 Insert line of code here.
print(list(foo))
[0, 4, 49, 81, 100]
-foo = map(lambda num : num ** 2, numbers)
15. class I:
    def __init__(self):
        self.s = 'abc'
        self.i = 0
        def __init__(self):
        return self
    def __next__(self):
        if self.i == len(self.s):
           raise StopIteration
         v = self.s[self.i]
         self.i +=1
         return v
for x in I():
    print(x, end='')
-The code will print abc
16. The complied Python bytecode is stored in files which have their names ending with:
-pyc
17. Which pip command would you use to uninstall a previously install package?
-pip uninstall packagename
18. try:
    raise Exception(1, 2, 3)
except Exception as e:
    print(len(e.args))
- The code will print 3
19. try:
    raise Exception
except BaseException:
    print("a")
except Exception:
    print("b")
except:
    print("c")
-a
20. class A:
      pass
class B(A):
      pass
class C(B):
      pass
print(issubclass(A, C))
-The code will print False
21. If you want to fill a byte array with data read in from a stream, which method you can use?
-The readinto() method
22. print(float("1.3"))
-will print 1.3
23. print(chr(ord('p) + 2))
-r
24. If there are more than one except: branch after the try: clause, we can say that:
-not more than one except: block will be executed
25. class Class:
     def __init__(self, vla = 0):
          pass
-object = Class(1, 2)
26. try:
   raise Exception
except:
   print("c")
except BaseException:
   print("a")
except Exception:
   print("b")
-The code will cause a syntax error 
27. def my_fun(n):
    s = '+'
    for i in range(n):
        s += s
        yield s
for x in my_fun(2):
    print(x, end='')
-++++++
28. numbers = [i*i for i in range(5)]
 Insert line of code here.
print(foo)
[1, 9]
-foo = list(filter(lambda x: x % 2, numbers))
29. def o(p):
    def q():
        return '*' * p
    return q
r = o(1)
s = o(2)
print(r() + s())
-***
30. The following statement:
from a.b import c
causes the import of:
-entity c from module b from package a
31. The sys.stderr stream is normally associaated with:
-the screen
32. What will be the output of the following code, located in the p.py file?
print(__name__)
-__main__
33. Assuming that the​ open() invocation has gone successfully, the following snippet:
for x in open('file', 'rt')) 
    print(x)
-read the file line by line
34. If a is a stream opened in read mod, the following line:
q = s.read(1)
will read:
-one character from the stream 
35. for line in open('text.txt', 'rt'):
-is invalid because open returns an iterable object
36. import os
os.mkdir('pictures')
os.chdir('pictures')
print(os.getcwd())
-The code will print the path to the created directory
37. file a.py
print("a", end='')
 file b.py
import a
print("b", end='')
 file c.py
print("c", end='')
import a
import b
-cab
38. class A:
     def __init__(self):
         pass
a = A(1)
print(hasattr(a, 'A'))
-The code will raise an exception
39. x = " \\"
print(len(x))
-will cause an error
40. Which of the following commands would you use to check pip ‘s version? (Select two answers)
-pip3 --version
-pip --version
