```
square = lambda x, y : x**y
print (square(10,2))
```

출력 값
100

람다를 사용하여 square 변수에 두 값을 제곱하도록 지정하여 출력

## Quiz

```
numbers = [111,26,37,48]
result = list(filter(lambda x : x%2 == 0 , numbers))
print(result)
```

출력값
[26, 48]

numbers 리스트를 지정한 후 필터에서 람다를 사용하여 2로 나눈 값의 나머지 0이 되는 수를 result에 저장하여 출력


## 과제

#### 코드

```
for i in range(2, 10):  // 변수 i를 2에서 9가 될때 까지 아래 명령을 실행
    for j in range(2, 10):  // 변수 j를 2에서 9가 될때 까지 아래 명령을 실행
        print(f"{i} * {j} = {i*j}")  // i*j의 값을 출력
```
![image](https://github.com/juneyoung0821/0321/assets/160203302/32d0a6cb-b812-43e9-b986-f539fe3860d9)
