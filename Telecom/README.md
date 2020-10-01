# Исследование исторических данных по компьютерным играм.

-------------------------------------------
 

### Краткое описание задачи

Нам были предоставленны данные по звонкам, количеству потраченного интернет-трафика и ежемесячным платежам по тарифам пользователей сотовой компании. На основе этих данных необходимо выбрать тариф, который приносит прибыль компании, чтобы спранировать рекламную кампанию.

-------------------------------------------

### В работе использованы:

- библиотеки Pandas, MatplotLib, SciPy, NumPy

-------------------------------------------

### Описание работы

1. Проведена предобработка данных, для выявления возможных ошибок при изменении типа данных применялась конструкция try-except.
2. Сгенерированы новые данные, например, объем израсходованного интернет-трафика по месяцам, и, соответственно, рассчитана ежемесячная выручка с каждого пользователя. 
3. Проведен исследовательский анализ данных: сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц.
4. Проведена проверка статистических гипотез:
    - средняя выручка пользователей тарифов различается;
    - средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов.
5. На основе анализа данных и проверке гипотез был определен перспективный тарифный план.