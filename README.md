# Python

<p align="center">
 <img src="https://user-images.githubusercontent.com/53357210/117002931-2b7aed80-ad1f-11eb-81c2-7ac564547023.png" alt="text" width="500"/>
</p>

## Content 

<!-- ### 목차 -->




### variable

#### 프로그램의 기본인 변수란 무엇인가

> 변수(variable)는 컴퓨터 프로그래밍에서 아직 알려지지 않거나 어느 정도까지만 알려져 있는 양이나 정보에 대한 상징적인 이름이다.

> 파이썬에서 변수의 선언을 하려면 다른 프로그래밍과는 조금은 다르다
> java 의 경우 변수의 타입이 존재한다

```java
String str="TEST";
```

> 위와 같이 자료형 + 변수명으로 선언을 한다
> 하지만 파이썬의 경우
> 자료형을 사용을 하지 않는다

 ```python
num = 100
```

> 위와 같은 식으로 변수명 만 사용을 한다
> 선언을 한 뒤 변수에 어떤한 변수를 넣는냐에 따라 변수의 자료형이 결정이 된다
> 아래는 예제 코드 이다 변수에 대한 것은 차차 알아가 보겠다

#### sample code

##### 정수 형

```python
num = 100
```

##### 문자 형

```python
str = "나는 문자"
```

##### 불리언 자료형

```python
bool = True
```

------


### 변수의 종류 와 문자열

#### 변수의 종류

> 파이썬의 경우
> 문자열 , 정수 , 소수 , 복소수 , 리스트 로 나뉜다

##### 문자열

``` python
a = type('a')
```

##### 문자열의 경우 아래와 같이 선언을 한다

```python
x = "test"
```

![R1280x0](https://user-images.githubusercontent.com/53357210/126778459-3fb9461e-4ab1-4616-a58b-b925af3fe50b.png)

```python
# 선언
x = "test"

print(x[0])

# 1 번부터 2 번까지
print(x[1:3])

# 2 번 까지
print(x[:3])

# 2 번부터
print(x[2:])
```

##### 정수

```
b = type(1)
```

##### 소수

```python
c = type(1.1)
```

##### 복소수

```
d = type(3 + 4j)
```

##### 리스트

```
f = type([1, 2, 3, 4, 5])
```

-------

### class

#### 클레스의 정의

> 파이썬에서 클래스를 사용하기 위해서는 class 라는 키워드를 꼭 붙여야합니다.

```python
class class_name : 
    pass:
```

> 클래스는 위와 같이 정의를 하면됩니다.
> 다음으로는 구조에 대하여 알아보겠습니다.
> 생성자와 내부 변수 선언과 내부 함수에 대하여 알아보겠습니다.

```python
class ClassName : 
    t = 0
    def __init__(self):
         self.t = 11
```

> 위는 클래스에서 생성자 선언에 입니다.
> `__init__` 은 생성자 키워드 입니다.
> `self` 라는 것은 클래스 내부의 변수에 접근할 수 있는 키워드 입니다.
> 위의 내용같은 것은 클래스 생성시 자동으로 `t` 라는 변수를 11 값으로 만들어 줍니다.

------

### function

#### 함수란 무엇인가?

> 사용자 정의 함수에 대하여 알아보겠습니다.
> 처음 함수를 작성을 할때는
> python 의 경우 def 라는 단어를 사용해서 함수를 작성을 해야됩니다.

```python
def [ function name ] ( [param] ) : 
```

> def 를 쓰고 함수 명 ( [ function name ] )을 넣어줍니다.
> 그 후에 인자 ( param ) 을 넣어주고  " : "  이 기호를 넣어줍니다.
> 다중 인자를 사용하고 하실때에는 param1 , param2 이런식으로 " , " 이 기호를 사용하여 만들어 줍니다.

##### 함수 선언

```python
def a():
    print("test success")
a()
```

> 함수 선언 후
> [function name]( [ parama] ) 형식으로 호출을 선언해줍니다.
> 안에 print 함수를 이용하여 출력 해봅니다.
> 출력이 된다면 함수 선언 후 사용에 성공하신겁니다.
> 다음으로는 함수 선언을 할때 인자를 선언을 해줍니다.

##### 인자를 통한 함수 호출

```python
def b(a):
    print(a)
b("test false")
```

##### 함수에서 인자 리턴

```python
def c(a):
return a
print(c("test"))
```

##### 함수내부에 지역변수를 선언하여서 리턴

```python
def add(a):
    b = 3
    return  a + b
print(add(10))
```

------------
