# Quant

## 퀀트기반 추천주 프로그램
* 2021-08-03 : 개발하던 프로그램 처음 업로드
* 2021-08-05 : WICS분류별 pbr그래프 오류 수정
* 2021-08-09 : colorbar 넣는 함수 추가
* 2021-08-10 : 관리를 위해 colorbar함수에서 custom_pyplot_colorbar 클래스로 변경
* 2021-08-12 : seaborn의 히트맵을 이용해 WICS 분류별로 영향을 주는 지표 파악

### 구성
* MultiProcessing을 통한 빠른 크롤링 구현
* matplotlib을 이용한 통계 데이터 시각화
  * 업데이트 예정 : plot의 색깔을 score에 따라서 연속적으로 분류한 다음, 해당 색상을 colorbar로 나타낼 예정
* MySQL을 이용하여 데이터 베이스 구성 (AWS RDS서비스 이용)
* 데이터베이스에 저장한 데이터를 불러와서 시각화 하는 형태
* 통계 데이터
  * 재무제표 데이터
  * 날짜별 가격 데이터
  * WICS(국제산업표준)을 기준으로 한 업종코드 분류
