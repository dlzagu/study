# 숫자형 
### 정수형 
정수형(Integer)이란 말 그대로 정수를 뜻하는 자료형을 말한다. 다음 예는 양의 정수와 음의 정수, 숫자 0을 변수 a에 대입하는 예이다.
```python
>>> a = 123
>>> a = -178
>>> a = 0
```

### 실수형 
파이썬에서 실수형(Floating-point)은 소수점이 포함된 숫자를 말한다. 다음은 실수를 변수 a에 대입하는 예이다.
```python
>>> a = 1.2
>>> a = -3.45
```
위 방식은 우리가 일반적으로 볼 수 있는 실수형의 소수점 표현 방식이다.
```python
>>> a = 4.24E10
>>> a = 4.24e-10
```

```python
>>> a = 4.24E10
>>> a = 4.24e-10
```

# 숫자형을 활용하기 위한 연산자
### 사칙연산 
```python
>>> a = 3
>>> b = 4
>>> a + b
7
>>> a * b
12
>>> a / b
0.75
```

### x의 y제곱을 나타내는 ```** ```연산자
이 연산자는 ```x ** y```처럼 사용했을 때 x의 y제곱 값을 돌려준다. 
```python
>>> a = 3
>>> b = 4
>>> a ** b
81
```

### 나눗셈 후 나머지를 반환하는 ```%``` 연산자
```python
>>> 7 % 3
1
>>> 3 % 7
3
```

### 나눗셈 후 몫을 반환하는 ```//``` 연산자

```/``` 연산자를 사용하여 7 나누기 4를 하면 그 결과는 예상대로 1.75가 된다.
```python
>>> 7 / 4
1.75
```
```python
>>> 7 // 4
1
```
1.75에서 몫에 해당되는 정수값 1만 돌려주는 것을 확인

*****
[출처](https://wikidocs.net/12)