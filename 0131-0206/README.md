# 병수님

-   문제 주소 : []()
-   접근 방법

```text
```

# 호근님

-   문제 주소 : []()
-   접근 방법

```text
```

# 태성님

-   문제 주소 : [프로그래머스 오픈채팅방](https://programmers.co.kr/learn/courses/30/lessons/42888)
-   접근 방법

```text
채팅방 입장, 퇴장, 이름변경시 채팅방에 표시된 이름을 바꿔줘야한다.
이전에 입장, 퇴장한 기록이 있더라도 다시 들어오거나 중간에 이름을 변경할시 이전 기록들도 동기화 해줘야한다.

최대 값이 100,000이므로 해쉬를 활용하여 문제풀이를 진행하였다.
입장 혹은 이름변경시에만 고유한 id값과 바뀐 이름이 매치되면 되기때문에 파이썬의 dict을 활용하여 값을 저장하였다.
이때 나가고 이름변경과 같은 예외사항이 없고 다시 들어왔을때 이름이 변경된 상태여도 고유한 id로 값이 저장되어있기때문에 대처가 된다.

따라서 첫 반복시에 입장 혹은 이름변경 액션이 일어나면 dict에 담아서 최종 이름을 가지고 있고
그 다음 반복문에 임장 혹은 퇴장에 대한 기록만 보여주면 되기때문에 입장 혹은 퇴장에 대한 액션에 대해서 저장된값과 지정문구를 배열에 담아서 처리했다.

이중 반복문을 활용하지 않고 똑같은 반복문을 2번 이용했기때문에 100,000 + 100,000 = 200,000이 되어 1초를 넘기지 않는다.(단순계산)
```

# 민호님

-   문제 주소 : []()
-   접근 방법

```text
```
