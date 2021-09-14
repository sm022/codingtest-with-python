### 정수형_integer
```python
a = 1000 # 양의 정수
print(a)

a= -7 # 음의 정수
print(a)

# 0
a = 0 
print(a)
```
```  
1000
-7
0
```
### 실수형_Real Number
```python
# 양의 실수
a = 157.93
print(a)

# 음의 실수
a = -1837.2
print(a)

# 소수부가 0일 때 0을 생략
a = 5.
print(a)

# 정수부가 0일 때 0을 생략
a = -7.
print(a)
```
```
157.93
-1837.5
5.0
-0.7
```
---
```python
# 10억의 지수 표현 방식
a = 1e9
print(a)

# 752.5
a = 75.25e1
print(a)

# 3.954
a = 3954e-3
print(a)
```
```
1000000000.0
752.5
3.954
```
---
```python
a = 0.3 + 0.6
print(a)

if a == 0.9:
  print(True)
else:
  print(False)
```
```
0.8999999999999999
False
```
---
```python
a = 0.3 + 0.6
print(round(a, 4))

if round(a, 4) == 0.9:
      print(True)
else:
      print(False)
```
```
0.9
True
```
---
```python
a = 7
b = 3

# 나누기
print(a/b)

# 나머지
print(a % b)

# 몫
print(a//b)
```
```
2.3333333333333335
1
2
```
---
```python
a = 5
b = 3

print(a**b)
```
```
125
``` 
