# 유용 꿀팁
- model compile 시..
  1. 분류
  - 이진분류: loss='binary_crossentropy'
  - 다중분류: loss='sparse_categorical_crossentropy'
  - one-hot coding: loss='categorical_crossentropy'
  2. 회귀: mean_squared_error, mean_absolute_error etc
