# Apache Kafka

Apache Kafka(아파치 카프카)는 LinkedIn에서 개발된 분산 메시징 시스템으로써 2011년에 오픈소스로 공개되었다. 대용량의 실시간 로그처리에 특화된 아키텍처 설계를 통하여 기존 메시징 시스템보다 우수한 TPS를 보여주고 있다.

### Kafka 특징
 - 분산 시스템에 유리, Scale out에 특화
 - 메시지를 파일 시스템에 저장하기 때문에, 데이터의 영속성이 보장

### Kafka의 구성요소
  - Producer
데이터 제공자, 메시지 제공자
특정 TOPIC의 메시지를 브로커에게 전달
 - Consumer
데이터 소비자, 메시지 소비자
특정 TOPIC의 메시지를 소비
 - Broker
 일반적으로 카프카 서버를 지칭, TOPIC을 기준으로 메시지 관리
 - Zookeeper
 - Topic
 - Partition
 - Offset
 - Leader/Follower
