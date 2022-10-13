# News_datapipeline


## 주제 : news 데이터 실시간 수집 및 배포

- 데이터파이프라인 구축시 설계 흐름의 이해를 위해 선정.

## 사용기술 

### 프로그래밍 언어
- python (3.9)

### 프로그램
- kafka
- Spark
- ElasticSearch
- Logstash
- Kibana
- Apache zeppelin
- Cloud Craft 

### 백엔드
- Python (3.9)
- Django
- Django ORM

### 저장환경
- Elastic Search

### 프론트엔드
- Bootstrap

## 데이터 파이프라인
- Crawling DATA
  - EC2(crawling) -> Kafka -> Logstash -> Elastic Search -> Kibana, Django
  
- Log Data
  - Django -> Kafka -> Logstash -> Spark -> Zeppelin

### 시스템 흐름도
![1507d508-d07a-4b46-8955-c346050d5f31](https://user-images.githubusercontent.com/76437951/195535643-228e9d81-63b7-4d11-b2d2-59d2728231a4.png)
