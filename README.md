# lad-tasks
В проекте 4 решеных задчачи по базовому JS для стажировки. Исходные данные представлены ниже. 



## Задача № 3
Задача 3. Быки и коровы

Компьютер загадывает число из нескольких различающихся цифр (от 3 до 6). Игроку дается несколько попыток на то, чтобы угадать это число.

После каждой попытки компьютер сообщает количество совпавших цифр стоящих не на своих местах, а также количество правильных цифр на своих местах.

Например загаданное число: 56478 предположение игрока: 52976

ответ: совпавших цифр не на своих местах - 1 (6), цифр на своих местах - 2 (5 и 7)
игра ведется до отгадывания


## Задача № 4
Боевой маг Евстафий сражается с лютым монстром.
Бой идет по ходам. Каждый ход компьютер (Лютый) случайно выбирает одно из доступных действий и сообщает, что он собирается делать. В ответ на это игрок (Евстафий) должен выбрать свое действие.

После происходит взаимное нанесение урона. Магическая броня блокирует магический урон, физическая броня блокирует физический урон.

После совершения действия, оно не может быть повторно выбрано в течение cooldown ходов

Бой идет до победы одного из противников.

Перед началом боя игрок выбирает сложность (начальное здоровье Евстафия)

Исходные данные:
- объект монстр,
- объект герой
