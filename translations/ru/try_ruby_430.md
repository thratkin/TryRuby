---
lang:   RU
title:  И на изумительный последок 
answer: не равно 100$
ok:     Так лучше
error:  Не может быть
---

Видите двойное равно __'abc' == 'def'__?

Это __==__ означает __проверка на равенство__. Одиночное равно используется для
__присваивания значения переменной__.

Чтобы немного вас запутать: вы можете использовать присваивание как аргумент
метода if:

    a = 0
    
    if a = 100
      puts "Выражение верно, но а сейчас: #{a}"
    else
      puts "#{a} не равно 100"
    end

Поменяйте = на == и посмотрите, что произойдет.

Я вам гарантирую, что вы будете часто забывать поставить двойное равенство. Я
сам иногда забываю.

### else (иначе)
В коде выше я добавил выражение else. Этот код выполняется в случае если
__выражение if__ вычисляется как ложь (false).

> Есть больше вариаций if-then-else. Больше информации вы можете почерпнуть
> <a href="http://www.ruby-doc.org/core/doc/syntax/control_expressions_rdoc.html" target="_blank">здесь</a>.
