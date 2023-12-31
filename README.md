# AI Talent Hackathon 2023_04.09.23
Исследование цитотоксичности материала является первым шагом в разработке медицинских препаратов, которые могут быть использованы либо в диагностических целях, либо в целях таргетинга. Проблема заключается в том, что на данный момент оценить токсичность наноматериалов возможно синтезировав их и проведя серию экспериментов. 
Решением проблемы является создание инструмента для оценки токсичности материала еще на этапе разработки. Это позволяет избежать лишних затрат и заранее исключить неэффективные стратегии.
Для подготовки нашего проекта мы воспользовались датасетом, предоставленным центром химии и искусственного интеллекта. В нем представлены данные ряда экспериментов, проводимых на различных клеточных культурах. Одна строчка в таблице представляет собой один эксперимент. В зависимости от исходных условий эксперимента, были получены значения выживаемости в процентах. Выживаемость интерпретируется как процент клеток, выживших после контакта с нанометриалом за время эксперимента и характеризует токсичность наноматериала.
В качестве инструмента, который решал бы описанную проблему мы выбрали десктопное приложение основанное на машинном обучении. В процессе разработки было создано несколько моделей машинного обучения и выбрана лучшая из них. На слайде вы можете увидеть сравнение метрик моделей, которые используются для оценки качества моделей. Random Forest показал наилучшие результаты, поэтому был выбран именно он.

 ![image](https://github.com/Riddars/Hakaton_04.09.23/assets/80139269/af39e673-03b6-4cf1-bce0-bebfb32bf404)


файл dataset_3090.csv - датасет до обработки

файл DF.csv - датасет после обработки

файл Hakaton_04_09(Data).ipynb - работа с обработанными данными (код обработки данных находился в другом файле и не имеет никакой ценности в рамках проекта)

файл AI Talent Hackathon 2023 Tkinter (1).ipynb - приложение (из-за возможных недоработок приложения было принято решение презентовать его код, а не само приложение)

файл AI talent boot camp_Hakaton.pptx - презентация проекта
