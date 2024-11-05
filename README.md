# bus-data

★: 유용한 것

## 교통카드빅데이터통합정보시스템

https://stcis.go.kr/

### 노선별 이용량 ★

- 전국
- (노선, 일자) -> (정류장, 이용자유형, 시간대) -> 승차량
- Crawl

### 노선별 차내재차인원 ★

- 전국
- (노선, 일자) -> (정류장, 이용자유형, 시간대) -> 재차인원
- Crawl

### 정류장별 이용량

- 전국
- (정류장, 일자) -> (노선, 이용자유형, 시간대) -> (승차량, 하차량)
- Crawl

### 정류장별 정차 노선수

- 전국
- (정류장, 일자) -> 노선
- Crawl

### 노선별 혼잡도

- 전국
- (노선{광역}, 일자) -> (정류장, 시간대) -> 혼잡도
- Crawl

## 경기도교통정보센터

https://gits.gg.go.kr/

### 노선별 버스 이용객수

- 경기
- (노선, 일시{평일|주말}, 시간대) -> 이용객수
- (노선, 일시{평일|주말}, 통행구분{단일|환승}) -> 이용객수
- xlsx

## 국가대중교통DB

https://kotsa.or.kr/ptc

### 대중교통 이용지표

#### 노선별 이용인원

- 전국
- 연도 -> (노선, 요일) -> 이용객수
- Crawl

#### 정류장별 이용인원

- 전국
- 연도 -> (정류장, 요일) -> (승차량, 하차량)
- Crawl

## 전국버스운송사업조합연합회

https://www.bus.or.kr/

### 버스노선 ★

https://www.bus.or.kr/support/route.asp

- 전국
- 지역 -> 웹사이트
- Crawl
