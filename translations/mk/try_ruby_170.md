---
lang:   MK
title:  Елементарно
answer: ^(12|35|47)$
load:   ticket = [12, 47, 35]
ok:     ОК
error:  Скоро до целта
---

Па, ги зачувавме нашите лото броеви во променливата ticket. Како сега да ги извадиме повторно надвор?

Веќе видовме дека можеме да го извадиме најголемиот број од низата со методот __max__. Слично, можеш да 
го извадиш __првиот__ или __последниот__ елемент од низата.
Но, што ако сакаш да извадиш некој конкретен елемент?

### [ ]
Ruby користи [ ] загради за да таргетира елемент.
Заградите се многу чести во Ruby.
Тие се како знаци кои се користат за да пронајдеш мета. Буквално.
Тие загради значат, "Јас барам ____". Подготвен, нишани!

Ајде да ги издвоиме сите лото броеви:

    puts ticket[0]
    puts ticket[1]
    puts ticket[2]

Зошто користиме [0], [1], [2]?

А не користиме [1], [2] и [3]? Да не е ова некаква Јапонска Зен работа?
Не, ние компјутерџиите сакаме да започнеме со броење од нула. Тоа всушност не е само во Ruby,
индексирањето _базирано на нула_ се користи во повеќето програмски јазици.

> Мало потсетување: можeш да го користиш __Copy__ копчето за да го копираш код примерокот во едиторот.
