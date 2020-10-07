Курс теории типов, КТ, осень 2020
==========================
## Материалы
+ [конспект лекций] (https://github.com/shd/tt2018-conspect)
+ [теоретические домашние задания] (https://github.com/shd/tt2020/blob/master/hw-theory.pdf)
+ [материал для первой половины курса] Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Предварительная лекция
### Лямбда-исчисление, базовые определения, примеры
+ Немного об истории
+ Лямбда-выражения, синтаксис
+ Альфа-эквивалентность, бета-редекс, бета-редукция
+ Булевские выражения, чёрчевские нумералы
+ Общие идеи про типизацию лямбда-исчисления
+ 
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 1
### Теорема Чёрча-Россера, Y-комбинатор
+ Бета-редуцируемость и параллельная бета-редукция
+ Теорема Чёрча-Россера
+ Комбинаторы: определение и примеры (I,S,K)
+ Рекурсия и Y-комбинаторы
+ Ленивые вычисления, нормальный порядок редукции
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 2
### Просто типизированное лямбда-исчисление
+ Импликационный фрагмент интуиционистского исчисления высказываний
+ Теорема о замкнутости импликационного фрагмента
+ Просто типизированное лямбда-исчисление по Карри и Чёрчу. Отличия между вариантами исчисления.
+ Сильная и слабая нормализация. Формулировка теоремы о сильной нормализации просто типизированного лямбда-исчисления
+ Теорема о выразительной силе просто-типизированного лямбда-исчисления.
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 3
### Вывод типов в просто типизированном лямбда-исчислении
+ 12 задач, 3 основных
+ Алгебраические термы, подстановки
+ Унификация термов
+ Алгоритм вывода типов
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 4
### Интуиционистская логика второго порядка, система F
+ Логика второго порядка, определения и простая модель
+ Выразимость связок через импликацию и квантор всеобщности
+ Система F
+ Выразительная сила и неразрешимость системы F
+ Экзистенциальные типы
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf
+ Доказательство неразрешимости системы F:
Aleksy Schubert, Second-Order Unification and Type Inference for Church-style Polymorphism
POPL '98: Proceedings of the 25th ACM SIGPLAN-SIGACT symposium on Principles of programming languages, January 1998 Pages 279–288
+ Экзистеницальные типы:
John C. Mitchell, Gordon D. Plotkin, Abstract Types Have Existential Type
http://homepages.inf.ed.ac.uk/gdp/publications/Abstract_existential.pdf

## Лекция 5
### Типовая система Хиндли-Милнера
+ Ранг типа
+ let-полиморифзм
+ Система HM
+ Алгоритм W вывода типов в HM
+ Y-комбинатор в HM
+ Мю-оператор, изо- и эквирекурсивные типы
### Где почитать
+ Luis Damas and Robin Milner, Principal type-schemes for functional programs
POPL'82: Proceedings of the 9th ACM SIGPLAN-SIGACT symposium on Principles of programming languages, ACM, pp. 207–212
+ Robin Milner, A theory of type polymorphism in programming (1978) // Journal of Computer and System Sciences, 1978, vol. 17, pp. 348--375
https://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.67.5276
+ Вывод типов с помощью ограничений
François Pottier, A modern eye on ML type inference; INRIA, September 2005
+ Бенджамин Пирс, Типы в языках программирования. Издательство «Лямбда пресс» & «Добросвет», Москва, 2011
