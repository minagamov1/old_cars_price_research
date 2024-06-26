# Old cars price research

### Подробное описание задачи и проекта

Перед нами стоит задача понять, какие факторы оказывают влияние на цены поддержанных автомобилей. Для этого мы будем использовать готовые датасеты с ресурса Kaggle и открытые данные об автомобилях с сайта auto.ru. Ниже представлена ссылка на используемый датасет:

- **cars**: [Kaggle Dataset](https://www.kaggle.com/datasets/slavapasedko/belarus-used-cars-prices)

Цель данного проекта состоит не только в предсказании цены, по которой выставлен конкретный автомобиль, но и в общей оценке рыночной стоимости автомобиля. Это может быть особенно полезно для людей, занимающихся перепродажей автомобилей. Используя модели машинного обучения, мы сможем попытаться предсказать рыночную стоимость конкретного автомобиля и оценить, стоит ли покупать его по указанной в объявлении цене.

### Используемые данные

Основной датасет с данными: `cars_2.csv`

Датасет который формируется на основе `cars_2.csv` и данных с auto.ru: `dataset_cars_with_mean_priceandmileage.csv`



## Состав проекта
Работа состоит из нескольких шагов:
- Загрузка данных
- Парсинг
- Изучение данных(EDA)
- Создание новых признаков
- Проверка гипотез
- Подготовка выборок
- Обучение разных моделей
- Анализ качества моделей.
- Выбор лучшей модели
- Подведение итогов

### Основные задачи проекта:

1. **Анализ факторов, влияющих на цену автомобилей**:
   - Определить, какие характеристики автомобилей (например, марка, модель, год выпуска, пробег, тип топлива и т.д.) оказывают наибольшее влияние на их стоимость.

2. **Использование готовых датасетов**:
   - Использовать готовые данные из датасетов на Kaggle и открытые данные с сайта auto.ru для анализа и моделирования.

3. **Создание модели предсказания цены**:
   - Разработать и обучить модели машинного обучения для предсказания цены автомобилей на основе их характеристик.

4. **Оценка стоимости автомобилей**:
   - Использовать модели для оценки рыночной стоимости автомобилей, что поможет определить, стоит ли покупать автомобиль по указанной в объявлении цене.

### Применение моделей машинного обучения:

- **Предсказание рыночной стоимости**:
  - Модели машинного обучения будут обучены на исторических данных для предсказания текущей рыночной стоимости автомобилей.

- **Рекомендации по покупке**:
  - Используя предсказанную стоимость, мы сможем рекомендовать, стоит ли покупать автомобиль по указанной в объявлении цене.

Этот проект имеет важное практическое значение для людей, занимающихся покупкой и продажей поддержанных автомобилей, так как предоставляет инструмент для оценки справедливой рыночной стоимости автомобилей.
