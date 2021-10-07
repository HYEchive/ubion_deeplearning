# ubion_deeplearning

!DOCTYPE html>
<html>
    <head>
        <img src="데이콘.png" width='1150' height='500'>
    </head>
    <body>
    </body>
</html>

1차 해커톤 신용카드 매출 예측

프로젝트 개요
1. Dataset을 확인하고 프로젝트의 목적에 맞는 전처리를 시행한다.
2. 각각의 데이터를 시각화하여 EDA를 시행한다.
3. RNN, SARIMA 모형을 활용하여 미래 3개월의 매출을 예측한다.

- 프로젝트 목표는 낮은 신용 점수, 무담보로 인해 어려움을 겪는 소상공인 대상 신용 대출 확대입니다.
- 상점 별 과거 2년간의 매출 데이터로 미래 3개월의 매출을 예측하는 것이 모델링의 목표입니다. 만약, 해당 상점이 3개월의 신용대출을 시행한다면, 매출 예측 데이터로 상환기간동안 상환 능력이 충분한지 확인하는 것이 최종 목표입니다.

프로젝트 목적
- EDA를 통한 시각화 및 전처리로 모델링을 시행해본다.

연구 요약
1.	국내 상점 매출 데이터 확인 (전처리 대상 데이터 선정)
2.	데이터 시각화 및 시계열 분석에 맞춘 전처리 진행
3.	EDA 시행으로 예측 모델 선정 (SARIMA, RNN을 후보로 선정)
4.	미래 3개월 매출 예측 및 시각화
