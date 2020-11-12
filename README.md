# Xproject
사용자 이동경로 기반 전염병 감염 정보 제공 시스템 개발


| 프로젝트 명 | 주최/기관 | 기간 | 역할 | 기여도 | Skill | 
| :---: | :---: | :---: | :---: | :---: | :--: |
| ICT·융합기술을 이용하여 전염병 예방과 확산을 방지 하는 방법은 없을까? | 과학기술정보통신부,상명대학교 | 2017.07 ~ 2019.06 | PE | 30% | Python, JavaScript|


## 1) 개발 내용
### <개요>
 * 사용자 이동경로 기반 전염병 감염 정보 제공 시스템 개발 및 구축
### <개발 내용>
 * 실내외 위치추적 알고리즘
     - 블루투스, 와이파이, GPS 신호를 기반으로 사용자의 위치를 실내와 실외에서 추적한다
 * 감염 확률 예측 알고리즘
     - 사용자의 위치추적 정보와 감염자와 감염 의심자들의 위치 정보를 기반으로 전염병에 대한 감염을 평가하여 감염 확률을 예측
 * 머신러닝 알고리즘
     - 제안된 위치추적과 감염확률 예측 알고리즘들의 정확도와 속도를 향상 시킨다.
     
### <역 할>
 * 데이터 수집
     - 영어 기반의 전세계 질병관련 뉴스를 수집한다.
     - 질병명(키워드)를 포함하는 뉴스를 일자별로 수집
     - NewsAPI.org의 API를 사용한다.
     - 사용 언어 Python , 데이터 타입 JSON
 * 데이터 전처리
     - 수집한 기사 내용 중 명사를 추출한다.
     - 수집한 기사 내용중 중복과 유사성을 확인한다.
     - 사용 언어 Python, 라이브러리 NLTK, Sift4
 * 데이터 시각화
     - 키워드 랭킹과 차트를 생성한다.
     - 사용 언어 JavaSript,JQuery, Ajax 라이브러리 dataTables.js, chart.js
  
## 2) 프로젝트 구성
### <시스템 구성도>
![System Architecture](https://user-images.githubusercontent.com/74284500/98909568-566d4d00-2505-11eb-901c-f998de07c215.PNG)


### <시스템 결과>
![System](https://user-images.githubusercontent.com/74284500/98909938-d2679500-2505-11eb-8dc6-36c69188b08c.PNG)


* A : 국가 선택
* B : 지역별 기사 수
* C : 키워드 랭킹
* D : 뉴스 통계 기반 차트
