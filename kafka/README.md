# Kafka

0. Kafka 스터디를 통해서 우리가 배울 것들
    - 기본 개념
      - Kafka의 특징
      - topic, partition
      - consumer, consumer-group, offset
      - HA, failover
    - Kafka 설치 및 클러스터 구성하기
      - ansible를 통해서 도커 컨테이너로 배포
    - Go 언어를 통해서 Producer/Consumer 만들어 보기

1. [Kafka란 무엇인가?](1_kafka.md)  
  1.1 카프카의 탄생 배경  
  1.2 카프카의 동작 방식과 원리  
  1.3 카프카의 특징  
  1.4 카프카의 확장과 발전

2. [카프카 디자인](2_kafka_design.md)  
  2.1 카프카 디자인의 특징  
  2.2 카프카 데이터 모델  
  2.3 카프카의 고가용성과 리플리케이션  
  2.4 모든 브로커가 다운된다면  

3. [카프카 프로듀서](3_kafka_producer.md)  
  3.1 콘솔 프로듀서로 메세지 보내기  
  3.2 프로듀서 주요 옵션  
  3.3 메세지 전송 방법  

4. [카프카 컨슈머](4_kafka_consumer.md)  
  4.1 컴슈머 주요 옵션  
  4.2 콘솔 컨슈머로 메세지 가져오기  
  4.3 파티션과 메세지 순서  
  4.4 컨슈머 그룹  
  4.5 커밋과 오프셋  

5. 카프카 운영가이드  
  TBD...  