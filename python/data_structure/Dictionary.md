# 딕셔너리 (Dictionary)
1. 메모리가 허용하는 범위 안에서 딕셔너리 내 다른 자료구조들도 중첩해서 사용 가능하다
2. {key: value} 를 한 쌍으로 구성되어 있고 중괄호를 사용한다
3. 딕셔너리 key에는 숫자도 가능하며 key는 중복될 수 없다 (만약 중복 될 경우 가장 마지막 값이 적용 된다)
4. 키(key)에는 숫자, 문자열, 불, 튜플 사용 가능

##  데이터 추가 / 삭제
```py
# 추가 예시
dict = {"name": "홍길동"}
dict["나이"] = 25
print(dict)
# {"name": "홍길동", "나이": 25}

# 삭제 예시
del dect["name"]
print(dict)
# {"나이": 25}
```

## 딕셔너리에 사용 가능한 함수
1. values() : 딕셔너리 내 값만 뽑아주는 함수
2. items() : 딕셔너리 내 키와 값을 뽑아주는 함수
3. keys() : 딕셔너리 내 키만 뽑아주는 함수
4. clear() : 딕셔너리 내 모든 키와 값을 지워주는 함수
5. get() : 해당 키에 해당하는 value 출력 (존재하지 않는 키를 호출하면 'None'을 출력한다)