# [**rsschool-cv**](https://sss-ecology.github.io/rsschool-cv/)
-----
# **Ekaterina Markova**
-----
### **Contact information:[](https://sss-ecology.github.io/rsschool-cv/cv#contact-information)**
* **Phone:** +7 (930) 47-28-597
* **E-mail:** pushistik680@gmail.com
* **Telegram:** brave_bumblebee

### **Briefly About Myself:[](https://sss-ecology.github.io/rsschool-cv/cv#briefly-about-myself)**
I want to learn Front-End Development in RSSchool!
-----

### **Education and scills:[](https://sss-ecology.github.io/rsschool-cv/cv#education-and-skills)**
*University: St. Petersburg State University, Faculty of Biology, bachelor's degree
*Scills:
    *HTML5, CSS3
    *JavaScript Basics
    *Git, GitHub
    *Python Basics
    *Bash, Jupyter Notebook
-----
### **Code example:[](https://sss-ecology.github.io/rsschool-cv/cv#code-example)**
```python
n = int(input())
a = list(map(int, input().split()))
m = int(input())
b = list(map(int, input().split()))
selo = list((enumerate(a, 1)))
sorted_selo = sorted(selo, key=lambda x: x[1])
bomba = list((enumerate(b, 1)))
sorted_bomba = sorted(bomba, key=lambda x: x[1])
s = [0 for i in range(len(sorted_selo)+1)]


def sb(a, n, s):
    k = 0
    l = 0
    while k < len(a) and l < len(n):
        u1 = abs(a[k][1] - n[l][1])
        u2 = abs(a[k-1][1] - n[l][1])
        if k+1 >= len(a):
            k = -1
        u3 = abs(a[k+1][1]-n[l][1])
        if abs(a[k][1]-n[l][1]) == min(u1, u2, u3):
            uno = n[l][0]
            dos = a[k][0]
            s[uno] = dos
            l += 1
        else:
            k += 1
    s.pop(0)
    return s


if len(sorted_bomba) == 1:
    for i in range(len(s)):
        s[i] = sorted_bomba[0][0]
    s.pop(0)
    print(*s)
else:
    print(*sb(sorted_bomba, sorted_selo, s))
```
-----

### **Courses:[](https://sss-ecology.github.io/rsschool-cv/cv#courses)**
* Web development for beginners: HTML и CSS on the [Stepik](https://stepik.org/) (completed)
    *![Stepic Score](https://stepik.org/certificate/aaea4d0847b836faa59eb1d014d040e739d021c3.png?resolution=medium)
* Python Programming on the [Stepik](https://stepik.org/) (completed)
    *![Stepic Score](https://stepik.org/certificate/f0b7b0ab8293ba68e89f9b90efa84397de8c4394.png?resolution=medium)
* JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/) (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

### **Languages:[](https://sss-ecology.github.io/rsschool-cv/cv#languages)**
- English - Intermediate/Upper-intermediate 
- Russian - Native