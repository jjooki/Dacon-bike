# Dacon-bike
[데이콘 2022 UOS 빅데이터 알고리즘 경진대회](https://dacon.io/competitions/official/236029/leaderboard)

## Description
Facebook의 Prophet 시계열 예측모델을 활용하여 학습하여 14등을 달성.
LSTM 모델과 Prophet 모델을 사용해본 결과 Prophet의 평가지표가 더 좋아 Prophet으로 학습한 버전을 최종 제출하였음.
Hyper-parmeter Tuning은 Grid search 기법을 활용하여 진행한 결과 최종적으로 MAE 1.92 달성하여 Private Leaderboard 14위에 랭크됨.

- bike.ipynb -> prophet 모델로 학습한 최종 제출본
- bike-lstm_ver.ipynb -> LSTM 모델로 학습한 내용
