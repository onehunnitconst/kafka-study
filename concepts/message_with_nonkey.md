### Key 값을 가지지 않는 메시지
- 메시지는 Producer를 통하여 토픽의 어떤 파티션으로 전송되어야 할 지 미리 결정이 된다.
- 키 값이 없는 경우, 라운드 로빈 및 스티키 파티션 등의 파티션 전략 등이 선택되어 메세지가 전송될 수 있다.
  - 라운드 로빈
- 토픽이 여러 개의 파티션을 가질 경우 메세지의 전송 순서가 보장되지 않은 채로 Consumeer에서 읽혀질 수 있다.