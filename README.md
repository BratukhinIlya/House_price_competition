# Предсказывание цен на недвижимость
В данном репозитории представлен код с **соревнования на Kaagle** - https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques. 

Считал `test.csv` и `train.csv`, объеденил их, обработал датафрейм, превратил **kатегориальные признаки в вещественные**, заполнил **пропуски**, удалил колонки с большим количеством пропусков - это можно посмототреть в файле `processing_dataframe.ipynb`, результат был разделен и записан соответсвенно `test_transform.csv` и `train_transform.csv'. В тестовой колонка с ценой заполнена **NaN**, а в тренировочной - заполнена **числами**

После этого переносимся в файл `Lin_regression_main.ipynb`. В нем обучил модель. Сначала реализовал численно **метод градиентного спуска** для одного признака, затем решил **аналитическим методом** задачу линейной регрессии (перемножением матриц), после чего подобрал **метрики качества** нашей модели

***Подробное решение со всеми пояснениями представлено в файлах `.ipynb`***
