# Проект "Анализ оттока клиентов банка «Метанпром»"

## Цели, план исследования проекта

###  Цель работы:

На основе анализа клиентской базы банка «Метанпром» подготовить информацию 
для отдела маркетинга о компактных однородных сегментах, подверженных оттоку 
и дать предложения по мероприятиям, которые можно провести, чтобы вернуть клиентов в банк 
или удержать сомневающихся от оттока.

Для достижения цели необходимо:
1. Провести исследовательский анализ данных и определите все значимые признаки отточности
2. Объединяя признаки отточности, сформируйте сегменты, отберите из них лучшие и дать 
по ним рекомендации.
3. Проверить гипотезы, которые могут помочь внести ясность в исследование, такие как:
    3.1 гипотеза о различия дохода между отточными и оставшимися клиентами
    3.2 любые другие гипотезы, способные выделить признак отточности.

### Вводная информация и описание источников данных

Анализ будет проведен на основании данных о клиентах банка «Метанпром» из датасета bank_scrooge.csv. Банк располагается в Ярославле и областных городах: Ростов Великий и Рыбинск.
Структура bank_scrooge.csv:

- USERID — идентификатор пользователя,Банки — Анализ оттока клиентов 2
- score — баллы кредитного скоринга,
- city — город,
- gender — пол,
- age — возраст,
- equity — количество баллов собственности
- balance — баланс на счёте,
- products — количество продуктов, которыми пользуется клиент,
- credit_card — есть ли кредитная карта,
- last_activity — активный клиент,
- EST_SALARY — оценочный доход клиента,
- сhurn — признак оттока

### План исследования

1. Первичное исследование и предобработка данных:
2. Исследовательский анализ данных.
    2.1 Визуализация и анализ корреляционных связей между переменными. 
    2.2 Определение значимых признаков отточности
    2.3 Сравнение типичных портретов клиентов, которые склонны и не склонны уходить из банка.
3. Проверка статистических гипотез.

    3.1    Проверка гипотезы о различии дохода между отточными клиентами, 
    и теми, которые остались.
    3.2    Дополнительная проверка гипотез: о различии баланса, возраста, баллов собственности, кредитного рейтинга между отточными клиентами и теми, которые остались.
    3.3 Для каждой гипотезы  определим  и обоснуем выбор использованного для оценки стат. критерия.

4.    Подготовка консолидированного вывода на основании предыдущего анализа, выделение основных стратегически важных показателей, влияющих на отток клиентов.
5.    Сегментация клиентов на основе выявленных стратегически важных показателей и их приоритизация, подготовка рекомендаций по выделенным сегментам.
6.    Подготовка итоговых выводов по результатам проекта.
7.    Подготовка презентации с основными выводами и описанием выявленных сегментов и рекомендаций для отдела маркетинга.

## Итоговые выводы и рекомендации

Сформированы сегменты и проведена их приоритизация, подготовлены рекомендации для отдела маркетинга, которые лягут в основу презентации. 
Презентация для отдела маркетинга: https://cloud.mail.ru/public/PNm9/dqAWxtrV7
