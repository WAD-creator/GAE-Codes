# GAE-Codes

```text
write these codes in main.py inside the folder u made on desktop
then run it in GAE, after that use port number to run localhost
```


# Google App Engine Programs (Python)

---

# C1 — Print Name, Seat Number, Department 5 Times

```python
print 'content-type: text/plain'

print

for i in range(5):
    print "Name: Sneha Singh"
    print "Seat No: 12345"
    print "Department: Computer Engineering"
    print
```

---

# C1 — Addition, Subtraction, Multiplication, Division

```python
print 'content-type: text/plain'

print

a = 20
b = 10

print "Addition =", a + b
print "Subtraction =", a - b
print "Multiplication =", a * b
print "Division =", a / b
```

---

# C1 — Largest Among Three Numbers

```python
print 'content-type: text/plain'

print

a = 10
b = 25
c = 15

if a > b and a > c:
    print "Largest number is", a

elif b > c:
    print "Largest number is", b

else:
    print "Largest number is", c
```

---

# C2 — Table of 10

```python
print 'content-type: text/plain'

print

for i in range(1, 11):
    print "10 x", i, "=", 10*i
```

---

# C2 — Fibonacci Series

```python
print 'content-type: text/plain'

print

a = 0
b = 1

print "Fibonacci Series:"

for i in range(10):
    print a,
    c = a + b
    a = b
    b = c
```
