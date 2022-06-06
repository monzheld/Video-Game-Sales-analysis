# 게임 설계를 위한 데이터 분석
데이터 분석을 통한 다음 분기 게임 설계 방안

<br>

## 제작 기간
2021.12.08 ~ 2021.12.13 

<br>

## 발표 자료
- [📘 Presentation](https://drive.google.com/file/d/1RxNMgKx9kUr-HchrBFE8JBSFIxFXwtul/view?usp=sharing)

<br>

## 프로젝트 개요
다음 분기에 어떤 게임을 설계해야 하는가

<br>

## 가설 검정
- 지역에 따라 선호하는 게임 장르가 다르다. -> **True**
- 연도별 게임의 트렌드가 있다. -> **True**

<br>

## 사용 기술

#### EDA
- pandas
- numpy
- matplotlib
- seaborn

#### 가설 검정
- statsmodels
- ANOVA Test

<br>

## 데이터셋
- Video Game Sales
- 데이터셋 크기: (16598, 9)
- [데이터 출처](https://www.kaggle.com/datasets/gregorut/videogamesales)

<br>

## 결론

#### 타깃 지역
- 북미 지역

#### 장르
- Shooter

#### 플랫폼
- PS(플레이스테이션)

=> 출고량이 Top 20인 게임의 지역별 출고량의 절반 이상을 차지한 **북미 지역을 타깃으로**, <br>
최근 5년간 출고량 Top 20인 게임의 장르에서 1위를 기록한 **Shooter 장르의 게임을** <br>
PS(플레이스테이션) 출시 이후 연도별 최고 출고량을 기록한 플랫폼과 최근 5년간 출고량 Top 20인 게임의 플랫폼에서 1위를 기록한 <br>
**PS(플레이스테이션)을 플랫폼으로 한 게임을 설계**.
