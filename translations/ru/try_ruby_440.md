---
lang:   RU
title:  Я голоден
answer: ^Я не голоден
ok:     Да
error:  Не может быть, что я голоден в 10 утра!
---

Мы делаем замечательный прогресс. Для вас это может быть не много, но имейте
ввиду, что вы __нисколько не знали Ruby__ всего 15 минут назад!

Последний шаг. Давайте свяжем все это вместе. Пускай это звенит вместе, как
прекрасный набор сверкающих курантов на пляже в великолепном солнечном свете!

Мы определим 2 метода и сделаем решение:

    def hungry?(time_of_day_in_hours)
      puts "Я голоден"
      true
    end

    def eat_an(what)
      puts "Я ем #{what}\n"
    end

    eat_an 'яблоко' if hungry?(14)

    eat_an 'яблоко' if hungry?(10)

Попробуйте изменить  метод __hungry?__ так, чтобы он печатал __"Я не голоден"__
и возвращал false когда время меньше 12.
