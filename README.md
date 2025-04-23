# 유용 꿀팁
- model compile 시..
  1. 분류
  - 이진분류: loss='binary_crossentropy'
  - 다중분류: loss='sparse_categorical_crossentropy'
  - one-hot coding: loss='categorical_crossentropy'
  2. 회귀: mean_squared_error, mean_absolute_error etc

- model.build((None,784)): none 옆의 수는 맘대로(클 수록 파라미터 수 증가) 근데 마지막에 빼먹지 말 것(sequential)
