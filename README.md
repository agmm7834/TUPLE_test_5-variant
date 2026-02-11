# test-tuple_5_variant
## 1-VARIANT

**1.** Quyidagi kod natijasida `a` o'zgaruvchisining qiymati nima bo'ladi?
```python
a = (1, 2, 3)
a = a + (4, 5)
```
A) (1, 2, 3, 4, 5)  
B) (1, 2, 3, [4, 5])  
C) TypeError  
D) (1, 2, 3)

**2.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30)
b = a[1:3]
print(type(b))
```
A) `<class 'list'>`  
B) `<class 'tuple'>`  
C) `<class 'str'>`  
D) TypeError

**3.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5)
print(a.index(3) + a.count(2))
```
A) 2  
B) 3  
C) 4  
D) 5

**4.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a[1] = 10
```
A) Ha, TypeError  
B) Yo'q, ishlaydi  
C) Ha, IndexError  
D) Ha, ValueError

**5.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15, 10, 20, 10)
print(a.count(10))
```
A) 1  
B) 2  
C) 3  
D) 4

**6.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = (4, 5)
c = a + b
print(len(c))
```
A) 2  
B) 3  
C) 5  
D) TypeError

**7.** Quyidagi kod natijasi nima?
```python
a = ((1, 2), (3, 4), (5, 6))
print(a[1][1])
```
A) 2  
B) 3  
C) 4  
D) 5

**8.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 40, 50)
b = a[::2]
print(b)
```
A) (10, 20, 30)  
B) (10, 30, 50)  
C) (20, 40)  
D) (10, 30)

**9.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 2, 4, 2)
try:
    x = a.index(2)
    y = a.index(2, x+1)
    print(y - x)
except:
    print(-1)
```
A) -1  
B) 1  
C) 2  
D) 3

**10.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = a * 2
print(len(b))
```
A) 3  
B) 6  
C) 9  
D) TypeError

**11.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15, 20, 25)
print(a[::-1][1:4])
```
A) (20, 15, 10)  
B) (25, 20, 15)  
C) (10, 15, 20)  
D) (15, 10, 5)

**12.** Quyidagi kod natijasi nima?
```python
a = tuple(range(10))
b = a[2:8:2]
print(sum(b))
```
A) 12  
B) 18  
C) 20  
D) 24

**13.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
del a[1]
```
A) Ha, TypeError  
B) Yo'q, ishlaydi  
C) Ha, IndexError  
D) Ha, ValueError

**14.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30)
b = (10, 20, 30)
print(a == b)
```
A) True  
B) False  
C) None  
D) TypeError

**15.** Quyidagi kod natijasi nima?
```python
a = (1, [2, 3], 4)
a[1].append(5)
print(a)
```
A) (1, [2, 3, 5], 4)  
B) TypeError  
C) (1, [2, 3], 4, 5)  
D) (1, [2, 3], 4)

**16.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5)
b = a[1:-1]
print(len(b))
```
A) 2  
B) 3  
C) 4  
D) 5

**17.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15)
b = list(a)
b.append(20)
print(len(a))
```
A) 3  
B) 4  
C) TypeError  
D) 5

**18.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = (4,)
c = a + b
print(c)
```
A) (1, 2, 3, 4)  
B) (1, 2, 3, (4,))  
C) TypeError  
D) (1, 2, 3, [4])

**19.** Quyidagi kod natijasi nima?
```python
a = tuple("Python")
print(len(a))
```
A) 1  
B) 5  
C) 6  
D) TypeError

**20.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 20, 40, 20)
print(a.index(20))
```
A) 0  
B) 1  
C) 2  
D) 3

**21.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = a
a = a + (4, 5)
print(b)
```
A) (1, 2, 3)  
B) (1, 2, 3, 4, 5)  
C) TypeError  
D) (4, 5)

**22.** Quyidagi kod natijasi nima?
```python
a = ()
print(type(a))
```
A) `<class 'tuple'>`  
B) `<class 'list'>`  
C) `<class 'NoneType'>`  
D) TypeError

**23.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5, 6, 7, 8)
b = a[1:7:2]
print(b)
```
A) (1, 3, 5, 7)  
B) (2, 4, 6)  
C) (2, 4, 6, 8)  
D) (1, 3, 5)

**24.** Quyidagi kod natijasi nima?
```python
a = (5,)
b = (10,)
c = a + b
print(len(c))
```
A) 1  
B) 2  
C) 3  
D) TypeError

**25.** Quyidagi kod natijasi nima?
```python
a = tuple([1, 2, 3])
b = tuple([1, 2, 3])
print(a is b)
```
A) True  
B) False  
C) None  
D) TypeError

---

## 2-VARIANT

**1.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
a = a * 3
print(len(a))
```
A) 3  
B) 6  
C) 9  
D) TypeError

**2.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 40)
b = a[-3:-1]
print(b)
```
A) (10, 20)  
B) (20, 30)  
C) (20, 30, 40)  
D) (30, 40)

**3.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 5, 15, 5, 20)
x = a.count(5)
y = a.index(5)
print(x + y)
```
A) 3  
B) 4  
C) 5  
D) 6

**4.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.append(4)
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, IndexError

**5.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 2, 4, 2, 5)
print(a.count(2))
```
A) 1  
B) 2  
C) 3  
D) 4

**6.** Quyidagi kod natijasi nima?
```python
a = (10,)
b = (20, 30)
c = a + b
print(c)
```
A) (10, 20, 30)  
B) (10, (20, 30))  
C) TypeError  
D) (10, 20)

**7.** Quyidagi kod natijasi nima?
```python
a = ((10, 20), (30, 40), (50, 60))
print(a[2][0])
```
A) 30  
B) 40  
C) 50  
D) 60

**8.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5, 6, 7, 8, 9)
b = a[::3]
print(b)
```
A) (1, 2, 3)  
B) (1, 4, 7)  
C) (3, 6, 9)  
D) (1, 3, 5, 7, 9)

**9.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 20, 40)
try:
    i1 = a.index(20)
    i2 = a.index(20, i1+1)
    print(i2)
except:
    print(-1)
```
A) -1  
B) 1  
C) 3  
D) 20

**10.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15)
b = a + a
print(len(b))
```
A) 3  
B) 6  
C) 9  
D) TypeError

**11.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 40, 50)
print(a[::-2])
```
A) (50, 30, 10)  
B) (50, 40, 30, 20, 10)  
C) (10, 30, 50)  
D) (40, 20)

**12.** Quyidagi kod natijasi nima?
```python
a = tuple(range(5, 20, 3))
b = a[1:4]
print(sum(b))
```
A) 24  
B) 30  
C) 33  
D) 36

**13.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.remove(2)
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, ValueError

**14.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15)
b = (5, 10, 15)
print(a is b)
```
A) True  
B) False  
C) None  
D) TypeError

**15.** Quyidagi kod natijasi nima?
```python
a = (10, [20, 30], 40)
a[1][0] = 99
print(a)
```
A) (10, [99, 30], 40)  
B) TypeError  
C) (10, [20, 30], 40)  
D) (99, [20, 30], 40)

**16.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5, 6)
b = a[2:5]
print(len(b))
```
A) 2  
B) 3  
C) 4  
D) 5

**17.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = list(a)
b.reverse()
c = tuple(b)
print(c)
```
A) (1, 2, 3)  
B) (3, 2, 1)  
C) [3, 2, 1]  
D) TypeError

**18.** Quyidagi kod natijasi nima?
```python
a = (10, 20)
b = (30,)
c = a + b
print(sum(c))
```
A) 30  
B) 60  
C) TypeError  
D) 50

**19.** Quyidagi kod natijasi nima?
```python
a = tuple("Hello")
print(a[1])
```
A) 'H'  
B) 'e'  
C) 'l'  
D) TypeError

**20.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 2, 4, 2, 5)
print(a.index(2, 2))
```
A) 1  
B) 2  
C) 3  
D) 5

**21.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = a
a = (4, 5, 6)
print(len(b))
```
A) 0  
B) 3  
C) 6  
D) TypeError

**22.** Quyidagi kod natijasi nima?
```python
a = (10,)
print(type(a))
```
A) `<class 'tuple'>`  
B) `<class 'int'>`  
C) `<class 'list'>`  
D) TypeError

**23.** Quyidagi kod natijasi nima?
```python
a = (0, 1, 2, 3, 4, 5, 6, 7, 8, 9)
b = a[2:8:3]
print(b)
```
A) (2, 5)  
B) (2, 5, 8)  
C) (2, 3, 4, 5)  
D) (3, 6)

**24.** Quyidagi kod natijasi nima?
```python
a = (100,)
b = a * 4
print(len(b))
```
A) 1  
B) 4  
C) 100  
D) TypeError

**25.** Quyidagi kod natijasi nima?
```python
a = tuple()
b = tuple()
print(a == b)
```
A) True  
B) False  
C) None  
D) TypeError

---

## 3-VARIANT

**1.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15)
a = a + (20, 25)
print(len(a))
```
A) 3  
B) 5  
C) 2  
D) TypeError

**2.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5)
b = a[1:4]
print(type(b))
```
A) `<class 'list'>`  
B) `<class 'tuple'>`  
C) `<class 'slice'>`  
D) TypeError

**3.** Quyidagi kod natijasi nima?
```python
a = (7, 14, 21, 14, 28, 14)
x = a.count(14)
y = a.index(14)
print(x * y)
```
A) 1  
B) 3  
C) 6  
D) 14

**4.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.clear()
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, ValueError

**5.** Quyidagi kod natijasi nima?
```python
a = (3, 6, 9, 6, 12, 6, 15)
print(a.count(6))
```
A) 1  
B) 2  
C) 3  
D) 4

**6.** Quyidagi kod natijasi nima?
```python
a = (1, 2)
b = (3, 4, 5)
c = a + b
print(len(c))
```
A) 2  
B) 3  
C) 5  
D) TypeError

**7.** Quyidagi kod natijasi nima?
```python
a = ((1, 2, 3), (4, 5, 6), (7, 8, 9))
print(a[1][2])
```
A) 3  
B) 5  
C) 6  
D) 8

**8.** Quyidagi kod natijasi nima?
```python
a = (2, 4, 6, 8, 10, 12, 14)
b = a[1::2]
print(b)
```
A) (2, 6, 10, 14)  
B) (4, 8, 12)  
C) (2, 4, 6, 8)  
D) (1, 3, 5)

**9.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15, 10, 20, 10)
try:
    x = a.index(10)
    y = a.index(10, x+2)
    print(y - x)
except:
    print(-1)
```
A) -1  
B) 2  
C) 3  
D) 4

**10.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30)
b = a * 2
print(b)
```
A) (10, 20, 30, 10, 20, 30)  
B) (20, 40, 60)  
C) TypeError  
D) (10, 20, 30)

**11.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5, 6, 7)
print(a[::-1][:3])
```
A) (7, 6, 5)  
B) (5, 6, 7)  
C) (1, 2, 3)  
D) (3, 2, 1)

**12.** Quyidagi kod natijasi nima?
```python
a = tuple(range(10, 30, 4))
b = a[::2]
print(sum(b))
```
A) 45  
B) 48  
C) 50  
D) 52

**13.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.pop()
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, IndexError

**14.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = (1, 2, 3)
print(a == b and a is not b)
```
A) True  
B) False  
C) None  
D) TypeError

**15.** Quyidagi kod natijasi nima?
```python
a = (5, [10, 15], 20)
a[1].extend([25, 30])
print(len(a[1]))
```
A) 2  
B) 3  
C) 4  
D) TypeError

**16.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 40, 50)
b = a[-4:-1]
print(len(b))
```
A) 2  
B) 3  
C) 4  
D) 5

**17.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30)
b = list(a)
b.sort(reverse=True)
c = tuple(b)
print(c[0])
```
A) 10  
B) 20  
C) 30  
D) TypeError

**18.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15)
b = (20,)
c = a + b
print(max(c))
```
A) 15  
B) 20  
C) 30  
D) TypeError

**19.** Quyidagi kod natijasi nima?
```python
a = tuple("Python")
print(a.count('o'))
```
A) 0  
B) 1  
C) 2  
D) TypeError

**20.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5)
print(a.index(4))
```
A) 2  
B) 3  
C) 4  
D) ValueError

**21.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30)
b = a
a = a + (40,)
print(len(b))
```
A) 3  
B) 4  
C) 0  
D) TypeError

**22.** Quyidagi kod natijasi nima?
```python
a = 10,
print(type(a))
```
A) `<class 'tuple'>`  
B) `<class 'int'>`  
C) `<class 'list'>`  
D) SyntaxError

**23.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
b = a[1:9:3]
print(b)
```
A) (2, 5, 8)  
B) (1, 4, 7)  
C) (2, 4, 6, 8)  
D) (3, 6, 9)

**24.** Quyidagi kod natijasi nima?
```python
a = (7,)
b = a * 5
print(sum(b))
```
A) 7  
B) 12  
C) 35  
D) TypeError

**25.** Quyidagi kod natijasi nima?
```python
a = tuple([10, 20, 30])
b = (10, 20, 30)
print(a == b)
```
A) True  
B) False  
C) None  
D) TypeError

---

## 4-VARIANT

**1.** Quyidagi kod natijasi nima?
```python
a = (2, 4, 6)
a = a * 2
print(sum(a))
```
A) 12  
B) 24  
C) 6  
D) TypeError

**2.** Quyidagi kod natijasi nima?
```python
a = (100, 200, 300, 400, 500)
b = a[2:]
print(b)
```
A) (100, 200)  
B) (300, 400, 500)  
C) (200, 300, 400)  
D) (400, 500)

**3.** Quyidagi kod natijasi nima?
```python
a = (4, 8, 12, 8, 16, 8)
x = a.count(8)
y = a.index(8)
print(x - y)
```
A) 1  
B) 2  
C) 3  
D) 4

**4.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.extend([4, 5])
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, ValueError

**5.** Quyidagi kod natijasi nima?
```python
a = (9, 3, 9, 6, 9, 12, 9)
print(a.count(9))
```
A) 1  
B) 2  
C) 3  
D) 4

**6.** Quyidagi kod natijasi nima?
```python
a = (5,)
b = (10, 15, 20)
c = a + b
print(c[1])
```
A) 5  
B) 10  
C) 15  
D) TypeError

**7.** Quyidagi kod natijasi nima?
```python
a = ((100, 200), (300, 400), (500, 600))
print(a[0][1])
```
A) 100  
B) 200  
C) 300  
D) 400

**8.** Quyidagi kod natijasi nima?
```python
a = (1, 3, 5, 7, 9, 11, 13, 15)
b = a[::4]
print(b)
```
A) (1, 5, 9, 13)  
B) (1, 4, 7, 10)  
C) (4, 8, 12)  
D) (1, 9)

**9.** Quyidagi kod natijasi nima?
```python
a = (7, 14, 21, 14, 28)
try:
    i1 = a.index(14)
    i2 = a.index(14, i1+1)
    print(i1 + i2)
except:
    print(-1)
```
A) -1  
B) 1  
C) 4  
D) 14

**10.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = a + a + a
print(len(b))
```
A) 3  
B) 6  
C) 9  
D) TypeError

**11.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 40, 50, 60)
print(a[-2::-2])
```
A) (50, 30, 10)  
B) (60, 40, 20)  
C) (50, 40, 30)  
D) (10, 30, 50)

**12.** Quyidagi kod natijasi nima?
```python
a = tuple(range(1, 15, 2))
b = a[2:6]
print(max(b))
```
A) 9  
B) 11  
C) 13  
D) 7

**13.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.insert(1, 10)
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, IndexError

**14.** Quyidagi kod natijasi nima?
```python
a = (100, 200, 300)
b = tuple([100, 200, 300])
print(a is b)
```
A) True  
B) False  
C) None  
D) TypeError

**15.** Quyidagi kod natijasi nima?
```python
a = (1, [2, 3], 4)
a[1][1] = 99
print(a[1][1])
```
A) 2  
B) 3  
C) 99  
D) TypeError

**16.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15, 20, 25, 30)
b = a[:4]
print(len(b))
```
A) 2  
B) 3  
C) 4  
D) 5

**17.** Quyidagi kod natijasi nima?
```python
a = (30, 10, 20)
b = list(a)
b.sort()
c = tuple(b)
print(c)
```
A) (30, 10, 20)  
B) (10, 20, 30)  
C) (20, 10, 30)  
D) TypeError

**18.** Quyidagi kod natijasi nima?
```python
a = (100, 200, 300)
b = ()
c = a + b
print(len(c))
```
A) 0  
B) 3  
C) 6  
D) TypeError

**19.** Quyidagi kod natijasi nima?
```python
a = tuple("Programming")
print(len(a))
```
A) 1  
B) 10  
C) 11  
D) TypeError

**20.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 40, 50)
print(a.index(30))
```
A) 1  
B) 2  
C) 3  
D) 30

**21.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15)
b = a
a = (20, 25, 30)
print(b[0])
```
A) 5  
B) 10  
C) 20  
D) TypeError

**22.** Quyidagi kod natijasi nima?
```python
a = 5, 10, 15
print(type(a))
```
A) `<class 'tuple'>`  
B) `<class 'list'>`  
C) `<class 'set'>`  
D) SyntaxError

**23.** Quyidagi kod natijasi nima?
```python
a = (2, 4, 6, 8, 10, 12, 14, 16)
b = a[::3]
print(b)
```
A) (2, 5, 8)  
B) (2, 8, 14)  
C) (3, 6, 9)  
D) (2, 6, 10, 14)

**24.** Quyidagi kod natijasi nima?
```python
a = (3,)
b = a * 3
print(b)
```
A) (3, 3, 3)  
B) (9,)  
C) TypeError  
D) (3,)

**25.** Quyidagi kod natijasi nima?
```python
a = ()
b = tuple([])
print(len(a) + len(b))
```
A) 0  
B) 1  
C) 2  
D) TypeError

---

## 5-VARIANT

**1.** Quyidagi kod natijasi nima?
```python
a = (3, 6, 9)
a = a + a
print(len(a))
```
A) 3  
B) 6  
C) 9  
D) TypeError

**2.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30, 40, 50)
b = a[:3]
print(b)
```
A) (10, 20, 30)  
B) (10, 20)  
C) (20, 30, 40)  
D) (40, 50)

**3.** Quyidagi kod natijasi nima?
```python
a = (2, 4, 6, 4, 8, 4)
x = a.count(4)
y = a.index(4)
print(x + y)
```
A) 2  
B) 3  
C) 4  
D) 5

**4.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.reverse()
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, ValueError

**5.** Quyidagi kod natijasi nima?
```python
a = (5, 5, 10, 5, 15, 5, 20)
print(a.count(5))
```
A) 2  
B) 3  
C) 4  
D) 5

**6.** Quyidagi kod natijasi nima?
```python
a = (100,)
b = (200, 300, 400)
c = a + b
print(sum(c))
```
A) 600  
B) 900  
C) 1000  
D) TypeError

**7.** Quyidagi kod natijasi nima?
```python
a = ((5, 10, 15), (20, 25, 30), (35, 40, 45))
print(a[2][1])
```
A) 30  
B) 35  
C) 40  
D) 45

**8.** Quyidagi kod natijasi nima?
```python
a = (0, 2, 4, 6, 8, 10, 12, 14, 16, 18)
b = a[2::3]
print(b)
```
A) (2, 5, 8)  
B) (4, 10, 16)  
C) (4, 7, 10)  
D) (0, 3, 6, 9)

**9.** Quyidagi kod natijasi nima?
```python
a = (3, 6, 9, 6, 12, 6)
try:
    x = a.index(6, 2)
    y = a.index(6)
    print(x - y)
except:
    print(-1)
```
A) -1  
B) 0  
C) 2  
D) 3

**10.** Quyidagi kod natijasi nima?
```python
a = (10, 20)
b = a * 3
print(max(b))
```
A) 10  
B) 20  
C) 30  
D) 60

**11.** Quyidagi kod natijasi nima?
```python
a = (5, 10, 15, 20, 25, 30, 35)
print(a[::-2])
```
A) (35, 25, 15, 5)  
B) (30, 20, 10)  
C) (35, 30, 25, 20)  
D) (5, 15, 25, 35)

**12.** Quyidagi kod natijasi nima?
```python
a = tuple(range(0, 25, 5))
b = a[1:4]
print(sum(b))
```
A) 25  
B) 30  
C) 35  
D) 40

**13.** Quyidagi kod xato beradimi?
```python
a = (1, 2, 3)
a.sort()
```
A) Ha, AttributeError  
B) Yo'q, ishlaydi  
C) Ha, TypeError  
D) Ha, ValueError

**14.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = (1, 2, 3)
print(a == b or a is b)
```
A) True  
B) False  
C) None  
D) TypeError

**15.** Quyidagi kod natijasi nima?
```python
a = (100, [200, 300], 400)
a[1].pop()
print(len(a[1]))
```
A) 0  
B) 1  
C) 2  
D) TypeError

**16.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5, 6, 7, 8)
b = a[-5:-2]
print(len(b))
```
A) 2  
B) 3  
C) 4  
D) 5

**17.** Quyidagi kod natijasi nima?
```python
a = (50, 30, 40, 20, 10)
b = sorted(a)
c = tuple(b)
print(c[2])
```
A) 20  
B) 30  
C) 40  
D) 50

**18.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5)
b = (6, 7, 8)
c = a + b
print(len(c))
```
A) 3  
B) 5  
C) 8  
D) TypeError

**19.** Quyidagi kod natijasi nima?
```python
a = tuple("Tuple")
print(a.index('p'))
```
A) 2  
B) 3  
C) 4  
D) ValueError

**20.** Quyidagi kod natijasi nima?
```python
a = (15, 30, 45, 60, 75)
print(a.index(45))
```
A) 1  
B) 2  
C) 3  
D) 45

**21.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3)
b = a
a = a * 2
print(len(b))
```
A) 0  
B) 3  
C) 6  
D) TypeError

**22.** Quyidagi kod natijasi nima?
```python
a = (10, 20, 30)
print(type(a[0]))
```
A) `<class 'tuple'>`  
B) `<class 'int'>`  
C) `<class 'list'>`  
D) TypeError

**23.** Quyidagi kod natijasi nima?
```python
a = (1, 2, 3, 4, 5, 6, 7, 8, 9)
b = a[1:8:2]
print(b)
```
A) (2, 4, 6)  
B) (2, 4, 6, 8)  
C) (1, 3, 5, 7)  
D) (1, 3, 5, 7, 9)

**24.** Quyidagi kod natijasi nima?
```python
a = (12,)
b = a * 2
print(sum(b))
```
A) 12  
B) 24  
C) 144  
D) TypeError

**25.** Quyidagi kod natijasi nima?
```python
a = tuple(range(5))
b = (0, 1, 2, 3, 4)
print(a == b)
```
A) True  
B) False  
C) None  
D) TypeError
