---
lang:   MK
title:  Припитомување на итрицата (Шекспирово дело)
answer: ^tame
ok:     Многу добро!
error:
---

Сега знаеш многу добро како да го користиш програмскиот јазик Ruby. Мислам, ги помина основите.
Сега, треба само да продолжиш да изучуваш што повеќе методи и да пробуваш што повеќе комплекси блокови.

Но, има една страна од Ruby за која не зборувавме. Дефинирање на твои методи.
__Точно така!__ Ајде да ги совладаме и нив.


Покрај тоа што можеш да ги користиш веќе дефинираните Ruby методи (како puts, sort, times), можеш
да дефинираш твои методи. Зошто тоа е добра идеја? Две причини:

### Да си ја направиш програма пократка
Ако една иста работа ти се повторува во повеќе делови од твојот код, полесно е
истиот тој код да се стави во посебен метод. Твојот код ќе биде пократок.

### Твојот код ќе биде лесен за читање
Претпостави си дека твојата програма треба да прави многу различни работи.
Да, ти __можеш__ да го ставиш кодот во една целина. Но, ќе биде многу тешко 
за разбирање и читање на истиот код подоцна.

Наместо тоа, можеш да го поделиш кодот на повеќе методи, при тоа да му дадеш
име од Англискиот јазик кое ќе биде лесно за разбирање. Ќе бидеш благодарен на себе за тоа подоцна.

Па, како дефинираме метод? Како во следниот пример:

    def tame( number_of_shrews )
    end
