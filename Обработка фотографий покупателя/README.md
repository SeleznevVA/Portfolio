# Обработка фотографий покупателя
[ipynb](https://github.com/SeleznevVA/Portfolio/blob/bf2f853639c1f2112447c28900936693c2e97cd7/%D0%9E%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D1%84%D0%BE%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%B9%20%D0%BF%D0%BE%D0%BA%D1%83%D0%BF%D0%B0%D1%82%D0%B5%D0%BB%D1%8F/%D0%9E%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D1%84%D0%BE%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%B9%20%D0%BF%D0%BE%D0%BA%D1%83%D0%BF%D0%B0%D1%82%D0%B5%D0%BB%D1%8F.ipynb)
## Описание проекта

Построение модели, которая по фотографии определит приблизительный возраст человека для анализа покупок и предложения товаров, которые могут заинтересовать покупателей конкртеной возрастной группы. Модель строится на основании размеченного датасета с фотографиями людей с указанием возраста. 

## Инструменты 
* pandas
* matplotlib.pyplot
* seaborn
* numpy
* tensorflow
* tensorflow.keras.preprocessing.image (ImageDataGenerator)
* tensorflow.keras.applications.resnet (ResNet50)
* tensorflow.keras.layers (GlobalAveragePooling2D, Dense)
* tensorflow.keras.models (Sequential)
* tensorflow.keras.optimizers (Adam)


## Общий вывод 
1. Модель сверточной нейронной сети построена на ResNet50.
2. Было задано 50 эпох и функция оптимизации для нахождения минимума Adam с шагом lr=0.00001.
3. Удалось достичь показателя МАЕ на тестовой выборке равного 6.45.
4. Итоговая модель позволяет определять возраст покупателей с погрешность до 6.45 лет.
