## [network]()

---

### 1. TCP와 UDP의 차이

| 프로토콜 종류  | TCP            | UDP                      |
| -------------- | -------------- | ------------------------ |
| 연결 방식      | 연결형 서비스  | 비연결형 서비스          |
| 패킷 교환 방식 | 가상 회선 방식 | 데이터그램 방식          |
| 전송 순서      | 전송 순서 보장 | 전송 순서가 바뀔 수 있음 |
| 수신 여부 확인 | 수신 여부 확인 | 수신 여부 확인하지 않음  |
| 통신 방식      | 1:1 통신       | 1:1 or 1:N or N:N 통신   |
| 신뢰성         | 높다           | 낮다                     |
| 속도           | 느리다         | 빠르다                   |
