## Команда Пыльных мышек
# Проект "Анализ пассажира потока и других показателей московского метрополитена"
## Структура проекта

### Часть 1: Подготовка данных
Мы подгрузили отобранные данные: три таблицы с различными признаками линий и станций московского метро. После нескольких преобразований (изменение формата, отбрасывание лишних строк и столбцов, замена недостающих значений), датасеты были подготовлены для дальнейшего использования. В блокноте подробно описаны все признаки и все шаги подготовки.
Так как таблицы различаются по содержанию и структуре, в ходе работы над проектом, мы много раз перегруппировывали данные и агрегировали показатели в зависимости от поставленных задач.
### Часть 2: Разведка
В этот раздел попали агрегация и добавление новых признаков (например, средний пассажиропоток по линиями за все периоды). Кроме того, были визуализированы интересующие нас показатели. Признаем, наши графики не столь искусны в своем исполнение, однако они нам значительно помогли в дальнейшем анализе, на их основе мы формулировали гипотезы. Мы также посмотрели на связи между признаками, полученные выводы соотнеслись с нашими общими представлениями о работе метрополитена.
### Часть 3: Гипотезы
В самом начале работы над проектом, нам было интересно сравнить пассажиропоток метро в разные времена года. В этом разделе мы поставили гипотезу о различии среднего потока зимой и летом и протестировали ее. Подобные шаги мы сделали и для сравнения среднего количества пассажиров весной и осенью.

### Часть 4: Машинное обучение
В этой части мы обучили модель, которая по статистике прошлых периодов (по кварталам) предсказывает будущий пассажиропоток по линиям метро. После первичного обучения на выборке (80/20) мы проверили работоспособность модели на таких критериях как MAPE, MSE (после кросс-валидации) и R^2, которые показали приемлемый для размеров нашей выборки результат. Модель имеет потенциал к практическому применению для расчета необходимого количества составов поездов, курсирующих на линии, исходя из прогноза пассажиропотока.



*P.S. Название нашей команды нам придумал ChatGPT*
