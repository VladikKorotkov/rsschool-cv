
# Korotkov Vladislav  
*FRONT END DEVELOPER*
![Текст с описанием картинки](img.jpeg)
---
## Personal data
- __Address__ - Belarus, Minsk
- __Phone__ - +375292909203
- __email__ - mr.vlad.korotkov@mail.ru
- __Discord__ - Vladik (@vladikkorotkov)
- ---
## Profile
Front end developer with little amateur experience, actively studying languages such as python, javascript, c++. I have a great desire to learn and develop my strengths.

---

## Experience
- Creating a chatbot in telegram for banking services
- Creating a website for the sale of household appliances

---

## Skills
1. MySQL
2. Python
3. HTML/CSS
4. Adobe Photoshop
5. business analysis

---

## Education
__Belarusian State University of Informatics and Radioelectronics__
_Specialization_ - software engineer economist (2025)

---
## Languages

- English(A2)
- Russian

---
## Code
```
number = input()
d = {'CM': 900, 'CD': 400, 'XC': 90, 'XL': 40, 'IX': 9, 'IV': 4, 'M': 1000, 'D': 500, 'C': 100, 'L': 50, 'X': 10,
     'V': 5, 'I': 1}
sum_n = 0
slicer = 2
while len(number):
    if len(number) < 2 and slicer == 2:
        slicer = 1
        continue
    slicee = number[:slicer]
    if slicee in d:
        sum_n += d[slicee]
        number = number[slicer:]
        slicer = 2
        continue
    if slicer == 2:
        slicer = 1
    else:
        slicer = 2

print(sum_n)
```