# VeChain predictor
### $${\color{red}ведется \space\space разработка \space\space улучшенной \space\space lstm \space\space модели}$$
## Описание
Проект представляет собой реализацию прогнозирования цены криптовалюты VeChain на открытых данных Yahoo Finance и метриках BitCoin с помощью различных моделей машинного обучения, таких как:
+ линейная регрессия
+ случайный лес
+ градиентный бустинг (выбран по по умолчанию)

Также используются нейронная модель LSTM и библиотеки ETNA для предсказания на несколько свечей вперед

## Реализации
Реализация быстрого прогнозирования только на одну свечу вперед в [Google Colab](https://colab.research.google.com/drive/1vQW4WqqpK13vLnZShP2gAIIBhCYtKuZc?usp=sharing)

Реализация прогнозирования на одну или несколько свечей вперед в [Google Colab](https://colab.research.google.com/drive/1lmYVVrRTb9j2ayD5FjdraixUjl3K-Wle#scrollTo=16adc7cb)

## Инструкция по работе с Google Colab
1) Подключение к удаленной среде выполнения

<img src="https://user-images.githubusercontent.com/78417431/218331959-68c17c86-80bf-4b8b-99d8-435c68ab5765.png" width="500">

2) Смена среды выполнения, переход на GPU

<img src="https://user-images.githubusercontent.com/78417431/218332025-662bdea1-0791-4037-a065-7a6e8a276f95.png" width="500"><img src="https://user-images.githubusercontent.com/78417431/218332033-efab03b2-bcd9-47ff-9ed0-81430eb41835.png" width="300">

3) Запуск скрипта

<img src="https://user-images.githubusercontent.com/78417431/218332258-5b08f4dc-f40a-46e6-8493-908eada8ffc0.png" width="500">

4) Переход к выводу программы

<img src="https://user-images.githubusercontent.com/78417431/218332309-61cf961c-508e-4576-b8a6-2a6bb0502fbe.png" width="700">

5) Вывод

<img src="https://user-images.githubusercontent.com/78417431/218332343-c7aa83e3-8778-414d-b4f1-daef20ae883e.png" width="700">
