- list 선언

```python
    Temps = list()
    Temps = []
```

```python
Temps.append("A")
Temps.append("B")
Temps.append("C")

```

- 추가,제거

```python

Temps.insert(1,'D')

# D제거
Temps.remove('D')

# 마지막 값 제거
Temps.pop()

Temps.sort()
Temps.sort(reverse=True)

Temps.reverse()

# 특정 위치값을 출력
Numbers.index(54)
```

```python
# List를 합치는 경우는 extend사용
Numbers = [1,2,3]
Number.extend(Numbers2)
Number.extend([10,15])
```