# Determining_the_Value_of_Cars_NumericalMethods

**Project Description**<br>
A service specializing in the sale of used cars is developing an application to attract new clients. In it, users can find out the market value of their car.

**Objective**<br>
To build a model capable of determining the value of a client's car.

We have data on the technical characteristics, configurations, and prices of other cars at our disposal.

**Criteria important to the client:**

- Prediction quality;
- Model training time;
- Model prediction time.

**Key Steps:**<br>

- Load the data.
- Study the data. Fill in missing values and process anomalies in the columns. If there are uninformative features among the attributes, remove them.
- Prepare samples for training models.
- Train different models, one of which should be LightGBM, and at least one should be non-boosting. Try different hyperparameters for each model.
- Analyze the training time, prediction time, and quality of the models.
- Based on the client's criteria, select the best model and verify its quality on the test sample.

**Notes:**<br>

- Use the RMSE metric to assess the quality of the models.
- The RMSE value should be less than 2500.
- Independently learn the LightGBM library and use its tools to build gradient boosting models.
- Obtain the execution time of a Jupyter Notebook code cell using a special command.
- The gradient boosting model may take a long time to train, so only change two or three parameters.
- If Jupyter Notebook stops working, delete unnecessary variables with the 'del' operator.

**Data Description**

- DateCrawled — date of downloading the listing from the database
- VehicleType — type of vehicle body
- RegistrationYear — year of vehicle registration
- Gearbox — type of transmission
- Power — power (hp)
- Model — car model
- Kilometer — mileage (km)
- RegistrationMonth — month of vehicle registration
- FuelType — type of fuel
- Brand — car brand
- Repaired — whether the car was repaired or not
- DateCreated — date of the listing's creation
- NumberOfPictures — number of car photographs
- PostalCode — postal code of the listing owner (user)
- LastSeen — date of the user's last activity

**Target Feature**

- Price — price (Euro)


**Описание проекта**<br>
Сервис по продаже автомобилей с пробегом разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. 

**Цель**<br>
Построить модель, которая умеет определять стоимость клиентского автомобиля. 

В нашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей.

**Критерии**, которые важны заказчику:
- качество предсказания;
- время обучения модели;
- время предсказания модели.

**Основные шаги:**<br>
- Загрузить данные
- Изучить данные. Заполнить пропущенные значения и обработать аномалии в столбцах. Если среди признаков имеются неинформативные, удалить их.
- Подготовить выборки для обучения моделей.
- Обучить разные модели, одна из которых — LightGBM, как минимум одна — не бустинг. Для каждой модели попробовать разные гиперпараметры.
- Проанализировать время обучения, время предсказания и качество моделей.
- Опираясь на критерии заказчика, выбрать лучшую модель, проверить её качество на тестовой выборке.

**Примечания:**<br>
- Для оценки качества моделей применять метрику RMSE.
- Значение метрики RMSE должно быть меньше 2500.
- Самостоятельно освоить библиотеку LightGBM и её средствами построить модели градиентного бустинга.
- Время выполнения ячейки кода Jupyter Notebook получить используя специальную команду.
- Модель градиентного бустинга может долго обучаться, поэтому стоит изменить у неё только два-три параметра.
- Если перестанет работать Jupyter Notebook, удалить лишние переменные оператором del.

**Описание данных** 
- DateCrawled — дата скачивания анкеты из базы
- VehicleType — тип автомобильного кузова
- RegistrationYear — год регистрации автомобиля
- Gearbox — тип коробки передач
- Power — мощность (л. с.)
- Model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- FuelType — тип топлива
- Brand — марка автомобиля
- Repaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя

**Целевой признак**
- Price — цена (евро)
