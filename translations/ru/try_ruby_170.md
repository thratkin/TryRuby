---
lang:   RU
title:  Элементарно
answer: ^(12|35|47)$
load:   ticket = [12, 47, 35]
ok:     Хорошо
error:  Почти
---

Мы сохранили лотерейные номера в переменную, а как их получить обратно?

Вы уже видели, как мы можем получить наибольший элемент списка, используя метод
__max__. Также вы можете получить __first__ (первый) или __last__ (последний)
элемент списка. А что, если вы хотите получить какой-то конкретный элемент?

### [ ]
Ruby использует квадратные скобки [], чтобы нацелиться на элемент. Квадратные
скобки очень распространены в Ruby. Они как прицелы, используемые для
выстраивания цели. Они означают: "Я ищу \_\_\_\_". Готов, целься! 

Давайте получим все номера из списка:

    puts ticket[0]
    puts ticket[1]
    puts ticket[2]

Почему мы используем [0], [1], [2]?

А не [1], [2] и [3]? Это какой-то японский дзен? Нет, просто мы, компьютерщики,
любим начинать отсчет с нуля. Это не только особенность Ruby, _индексирование,
основанное на нуле_, испольуется в большинстве языков программирования.

> Небольшое напоминание: вы можете использовать кнопку __Copy__, чтобы
> скопировать демонстрационный код в редактор.
