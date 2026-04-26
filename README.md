# 포트폴리오 기록

이 저장소는 포트폴리오를 만들기 위해 공부한 내용과 코딩 연습 과정을 정리하고 기록하기 위해 만든 공간입니다.

## 주요 내용
- 코딩 연습
- 프로젝트 준비 과정
- 포트폴리오 정리

---

## 코드 연습

1. 인사 출력
```python
print("Hello, World!")

2. 리스트 컴프리헨션
nums = [x*2 for x in range(5)]
print(nums)

3. 람다 함수
add = lambda a, b: a + b
print(add(3, 5))

4. 딕셔너리 사용
user = {"name": "kim", "age": 24}
print(user["name"])

5. 조건 한 줄 처리
num = 7
print("짝수" if num % 2 == 0 else "홀수")

6. set 중복 제거
data = [1, 2, 2, 3, 3]
print(set(data))

7. zip 사용
names = ["a", "b"]
scores = [90, 80]
print(list(zip(names, scores)))

8. map 함수
nums = [1, 2, 3]
print(list(map(lambda x: x*2, nums)))

9. 문자열 뒤집기
s = "python"
print(s[::-1])

10. 파일 쓰기
with open("test.txt", "w") as f:
    f.write("hello")
