
## 해쉬 테이블과 해쉬 맵

- 두가지 모두 key, value를 활용해 빠른 데이터 접근을 허용합니다.
- 내부적으로 배열을 사용합니다
- O(1) 시간 복잡도 이지만, 내부적으로 인덱스가 충돌한 경우 O(n)까지 증가합니다.

### 차이점

- 해시 테이블은 null을 허용하지 않기 때문에 쓰레드 세이프하다는 장점
- 해시 맵은 null을 허용하기 때문에 쓰레드 세이프하지 않다 

### 쓰레드 세이프
- 동시에 쓰레드가 접근해도 프로그램 실행에 문제가 없는 [Array와 Linked LIst.md](Array%EC%99%80%20Linked%20LIst.md)상태 