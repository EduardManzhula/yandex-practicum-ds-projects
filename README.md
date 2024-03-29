# Проекты по Data Science на Яндекс.Практикуме
Проекты были выполнены в ходе обучения на курсе [Яндекс.Практикум по Data Science]

## Список проектов

### 1. Исследование музыкальных предпочтений больших городов
Проект посвещен изучению музыкальных предпочтений клиентов сервиса Яндекс.Музыка из Москвы и Санк-Петербурга. Проводится предобработка данных: переименование столбцов, обработка пропусков и дубликатов. Анализ данных отвечает на вопросы:
   
- Действительно ли музыку в разных городах слушают по-разному?
- Утро понедельника и вечер пятницы — разная музыка или одна и та же?
- Москва и Питер — две разные столицы, два разных направления в музыке. Правда?
### 2. Исследование надёжности заёмщиков
Исследование ведется в интересах кредитного отдела банка. Входные данные — статистика о платёжеспособности клиентов. Обрабатываются артифакты, аномалии, пропуски в данных. Изменяются типы данных, обрабатываются дубли. Проводится лемматизация целей кредита. Осуществляется категоризация данных, выделяются словари. Анализ данных сосредоточен на изучении связи кредитоспособности с наличием детей, семейным положением, уровнем дохода, целями.
### 3. Исследование объявлений о продаже квартир
Проект построен на данных сервиса Яндекс.Недвижимость по продажам квартир в Санкт-Петербурге. Проводится предобработка данных: обработка пропусков, изменение типов данных, обработка дублей. Рассчитывается цена квадратного метра, соотношение жилой к общей площади, отношение площади кухни к общей и ряд других параметров. Исследовательский анализ данных выводит общие статистические характиристики, графики. Обрабатываются выбросы. Изучаются зависимости по коэффициентам Пирсона. Выводится зависимость цены от удаленности, населенного пункта и других параметров.
### 4. Определение перспективного тарифа для телеком компании
Компания «Мегалайн» — федеральный оператор сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Проводится предварительный анализ тарифов на небольшой выборке клиентов. В нашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Проанализируем поведение клиентов и сделаем вывод — какой тариф лучше. Предобработка данных состоит в изменении типов, обработке пропусков, дублей, выбросов. Рассчитывается помесячная выручка. Исследовательский анализ данных выводит общие статистические характеристики и графики. Формулируются гипотезы о средних выручках и проверяются методом т-критерия Стьюдента. Сравниваются выручки в Москве и остальных регионах.
### 5. Потециально популярный продукт для магазина компьютерных игр
Выявляются определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. Данные готовятся переименованием столбцов, обработкой пропусков, изменением типов. Рассчитываются суммарные продажи по регионам. Исследовательский анализ данных сосредоточен на изучении особенностей, зависимостей и распределения в данных, выводятся графики, коэффициенты Пирсона. Составляется типичный портрет для пользователя для каждого региона. Формулируются гипотезы по рейтингам на разных платформах и проверяются методом т-критерия Стьюдента. Делается вывод о том, какие игры будут успешны.
### 6. Рекомендация тарифов для клиентов мобильного оператора
Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Строится модель для задачи классификации, которая выберет подходящий тариф.
### 7. Прогнозирование оттока клиентов банка
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Спрогнозируем, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Для обучения модели предсказания ведется борьба с дизбалансом в целевом признаке.
### 8. Наиболее прибыльный регион бурения скважин
Проект выполняется для добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину.
Нам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Построим модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируем возможную прибыль и риски техникой Bootstrap.
### 9. Прогнозирование коэффициентов восстановление золота из руды
Подготовим прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
Модель будет предсказать коэффициент восстановления золота из золотосодержащей руды. В нашем распоряжении данные с параметрами добычи и очистки.
### 10. Предсказание страховых выплат с защитой персональных данных
Страховой компании «Хоть потоп» требуется модель предсказания размера страховых выплат по некоторому набору персональных данных клиентов. При этом нужно защитить данные клиентов от восстановления неавторизованными пользователями. Должна быть исключена необходимость передавать неизмененные данные в модель предсказания.

[Яндекс.Практикум по Data Science]: https://praktikum.yandex.ru/data-scientist/