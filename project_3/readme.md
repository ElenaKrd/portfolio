# Исследование данных о продажах компьютерных игр.
##  Краткое описание проекта.
Необходимо произвести определённые манипуляции с предоставленными данными, чтобы выявить наиболее популярные для продажи игры. Прогноз составляется на 2017 год. По условиям технического задания определяющим является выявить принцип работы с данными, на основе которого в последующем можно будет строить прогнозы на любой последующий год.
##  Цель проекта.
Выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании на следующий календарный год..
## Навыки и инструменты
- pandas 
- matplotlib.pyplot 
- %matplotlib inline
- %config InlineBackend.figure_format='retina'
- seaborn 
-  numpy 
- scipy stats 
  ## Выводы и рекомендации заказчику исследования.
- Учесть выводы исследования при планировании рекламных компаний на каждый регион по отдельности. У пользователей Европы и Америки много общего,тогда как пользователь Японии во многом - другой.
-  По региону Северная Америка:рекламный бюджет направитьна платформы X360 и PS4; учесть стабильность выручки при распределении рекламного бюджета по жанрам и отдать предпочтение жанрам Shooter и Sports (они демонстрируют стабильность выручки при продажах); рейтинг ESRB учитывать обязательно, самыми популярными будут игры с маркировкой М и Е.
- По региону Европа: рекламный бюджет направитьна платформы PS3 и PS4; учесть стабильность выручки при распределении рекламного бюджета по жанрам и отдать предпочтение жанрам Shooter и Sports (они демонстрируют стабильность выручки при продажах), рейтинг ESRB может быть не актуален, поскольку во многих европейских странах естьсвой рейтинг для игр;
- По региону Япония: рекламный бюджет направитьна платформы 3DS и PS3; учесть стабильность выручки при распределении рекламного бюджета по жанрам и отдать предпочтение жанрам Role-Playing и Misk, рейтинг ESRB не учитывать,поскольку в азиатских странах есть свой рейтинг для игр; учесть наибольшую популярность игр для подростков.
- Рейтинг критиков имеет незначительное влияние на продажи, можно использовать это при распределении бюджета. Рейтинг пользователей влияния на продажи не имеет.
- Использовать принцыпы данного исследования при прогнозировании рекламных компаний на последующие годы.

