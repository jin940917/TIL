# 집합 (Set)
1. 출력 형식이 중괄호{} 이며 중복값을 허용하지 않는다.
2. 정해진 순서가 없고 자동 정렬된다.
3. 인덱싱을 할 수 없고 참조하기 위해서는 자료형 변환이 필요하다 (list, tuple, dictionary)
```py
# 생성 방법
s1 = set([1, 2, 3]) # {1, 2, 3}
s2 = set("asdf")  # {a, d, f, s}
```
## 요소 수정
1. add() : 요소 하나 추가
2. update([요소1, 요소2, ..]) : 요소 여러개 추가
3. remove(요소) : 해당 요소 제거
```py
# 인수 하나 추가
s4.add(0)

#인수 여러개 추가
s4.update([100, 200, 300])

#인수 제거
s4.remove(0)
```