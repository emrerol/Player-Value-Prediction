# Makine Öğrenmesi Dersi Ödevi

## Projenin Amacı

Football Manager oyunu performans verilerini kullanarak futbolcu değer tahmini yapmak

## Kullanılan Veri Seti

https://www.kaggle.com/datasets/gabrielabilleira/football-manager-2022-player-data


## Sonuçlar

RandomForestRegressor modeli için cross-validation sonuçları:
Best Model Score: 0.9988778337776075
Average MSE Score: 10261860799896.66
Average MAE Score: 496679.3734674969
Average R2 Score: 0.9920554183926515

----------------------------------------------------------------------------

KNeighborsRegressor modeli için cross-validation sonuçları:
Best Model Score: 0.9995943773422278
Average MSE Score: 8866575740286.371
Average MAE Score: 418982.379962406
Average R2 Score: 0.993494958830413

----------------------------------------------------------------------------

AdaBoostRegressor modeli için cross-validation sonuçları:
Best Model Score: 0.9895185429610331
Average MSE Score: 13697250272149.705
Average MAE Score: 2871053.648356795
Average R2 Score: 0.9823593299161605

----------------------------------------------------------------------------

SVR modeli için cross-validation sonuçları:
Best Model Score: -0.08521800450988137
Average MSE Score: 1029237724917301.8
Average MAE Score: 11212415.748412827
Average R2 Score: -0.1296270633919227

----------------------------------------------------------------------------

LinearSVR modeli için cross-validation sonuçları:
Best Model Score: 0.9999990809184789
Average MSE Score: 3978423901927.0195
Average MAE Score: 361723.5468528856
Average R2 Score: 0.9972723750295813

----------------------------------------------------------------------------

MLPRegressor modeli için cross-validation sonuçları:
Best Model Score: 0.9999816467284356
Average MSE Score: 401022660587.7018
Average MAE Score: 172590.6174745033
Average R2 Score: 0.9992965707993919

----------------------------------------------------------------------------