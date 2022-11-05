### Serialized Message
- Producer와 Consumer 간에는 Serialized된 메세지만 전송할 수 있다.
- Producer에서 보내는 레코드는 직렬화된 Byte Array로 브로커에 전달, Consumer는 이를 받아서 역직렬화를 수행한다.

### 자바 객체의 직렬화
자바 객체를 객체의 유형, 데이터의 포맷, 적용 시스템에 관계없이 이동/저장/복원을 자유롭게 하기 위해서 바이트 배열 형태로 저장하는 것!