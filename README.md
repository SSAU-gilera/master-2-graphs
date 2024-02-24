# Сетевое планирование на графах

#### Додонова Наталья Леонидовна

1 курс 2 полугодие (2 семестр)

### Варианты

| Работа | Вариант |
| :------------------ | :------ |
|ИДЗ                | 1       |

# ИДЗ

1. Построить сетевой график для максимальной (tпес) продолжительности всех его работ, рассчитать наиболее ранние и наиболее поздние сроки наступления событий, найти критический путь, определить полные и независимые резервы времени всех работ и коэффициенты напряженности некритических дуг.

2. Для трехпараметрической модели найти ожидаемое время выполнения проекта, определить вероятность выполнения проекта не позднее заданного срока, найти интервал гарантированного (с вероятностью Р = 0,9973) времени выполнения проекта, оценить максимально возможный срок выполнения проекта с заданной надежностью. Выполнить те же расчеты для двухпараметрической модели. Сравнить результаты.

3. Считая tпес продолжительностью работы с минимальной допустимой интенсивностью (tпес = tmax), а tопт – продолжительностью работы с максимальной возможной интенсивностью (tопт = tmin), найти оптимальный по стоимости вариант выполнения проекта. Минимизировать стоимость проекта при минимально возможном сроке его исполнения.

| Работа | Опирается на работы |tпес | tвер | tопт | Стоимость сокращения работы на один день, Sk |
| :----- | :------------------ | :-- | :--- | :--- | :------------------------------------------- |
|b1      | -                   | 10  | 5    | 3    | 6                                            |
|b2      | -                   | 7   | 6    | 4    | 8                                            |
|b3      |b1                   | 5   | 4    | 2    | 4                                            |
|b4      |b1                   | 2   | 2    | 1    | 6                                            |
|b5      |b1                   | 6   | 4    | 2    | 7                                            |
|b6      |b3, b4               | 6   | 3    | 1    | 4                                            |
|b7      |b2                   | 9   | 6    | 3    | 5                                            |
|b8      |b3, b4, b5           | 3   | 2    | 1    | 9                                            |
|b9      |b6, b8               | 4   | 2    | 1    | 5                                            |
|b10     |b3, b4, b5           | 11  | 8    | 3    | 10                                           |
|b11     |b6, b8               | 9   | 5    | 2    | 7                                            |
|b12     |b7, b9               | 8   | 6    | 4    | 8                                            |

Директивный (заданный) срок выполнения проекта Tдир = 22 дня.

Заданная надежность γ = 0,90.

Стоимость одного дня проекта равна 12 денежным единицам: S = 12.
