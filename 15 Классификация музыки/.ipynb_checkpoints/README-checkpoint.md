Название проекта:<br>
Классификация музыки

Описание проекта:<br>
Вы сотрудник Отдела Data Science популярного музыкального стримингового сервиса "МиФаСоль". Сервис расширяет работу с новыми артистами и музыкантами, в связи с чем возникла задача - правильно классифицировать новые музыкальные треки, чтобы улучшить работу рекомендательной системы.

Навыки и инструменты:
- pandas
- matplotlib
- seaborn
- scikit-learn
- numpy
- catboost

Выводы:<br> 
В этом проекте мы разработали модель для классификации музыкальных треков по жанрам для музыкального стримингового сервиса "МиФаСоль".

Мы начали с загрузки и предварительной обработки данных, включая обработку пропущенных значений и создание новых признаков. Затем мы провели анализ данных, чтобы понять распределение данных и взаимосвязи между признаками.

Далее, мы обучили и проверили несколько моделей классификации на наших данных, включая CatBoost, Random Forest, SVC и Logistic Regression. Модель CatBoost показала наилучшую точность, поэтому мы выбрали ее для дальнейшего тюнинга гиперпараметров с использованием RandomizedSearchCV.

После того как мы нашли оптимальные гиперпараметры для нашей модели, мы обучили ее на полном наборе обучающих данных и проверили точность с помощью кросс-валидации. Затем мы использовали эту модель для предсказания жанра музыки на тестовых данных.

Наконец, мы изучили важность признаков нашей модели CatBoost. Это позволило нам понять, какие признаки наиболее важны для нашей модели при прогнозировании жанра музыки.

В результате у нас есть обученная модель, которую можно использовать для классификации жанра музыки на новых данных! Это поможет улучшить работу рекомендательной системы сервиса "МиФаСоль".
