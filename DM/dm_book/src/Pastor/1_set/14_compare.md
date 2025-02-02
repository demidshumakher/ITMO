# Билет 14

##  Сравнение мощностей. Определение, теорема Кантора-Бернштейна (формулировка), континуум-гипотеза. Теорема Кантора о мощности множества всех подмножеств.

### Сравнение мощностей

#### Определение
> Мощность множества X больше мощности множества Y, если эти
 множества неравномощны и в X есть подмножество, равномощное Y.
 Обозначение: |X| > |Y|

### Теорема Кантора-Бернштейна
> Теорема (Г.Кантор, Ф.Бернштейн)
 Если существуют подмножества $X_0 \subset X$ и $Y_0 \subset Y$, такие, что $X_0 ∼ Y$ и
 $Y_0 ∼X$, то $X ∼Y$. (б/д)


 • Тем самым, утверждения |X| > |Y| и |Y| > |X| не могут быть выполнены
 одновременно. То есть сравнение мощностей корректно.
 • При помощи аксиомы выбора можно доказать, что любые две мощности
 сравнимы. То есть для любых X и Y выполнено ровно одно из следующих
 трех утверждений: либо |X| > |Y|, либо |Y| > |X|, либо X ∼ Y.
 
> • Мощность конечного множества тем больше, чем больше в нем элементов.
> • Мощность счётного множества больше мощности любого конечного множества.
> • Обратно, если |X| < a, то X конечно.
> • Мощность континуума больше мощности счетного множества.
> • Континуум-гипотеза. Не существует такого множества X, что a < |X| < c. (Мощность счётного множества обозначается через a. Мощность континуума обозначается через c.)
> • К.Гёдель и П.Коэн доказали, что континуум-гипотезу невозможно ни доказать ни опровергнуть в рамках формальной теории множеств.


### Теорема Кантора о мощности множества всех подмножеств

> ### Теорема
>  Теорема (Г.Кантор)
 Для любого множества X выполнено |P(X)| > |X|.

> ### Доказательство. 
> Пусть Y = {{x} | x ∈ X}. \
> • Очевидно, что Y ∼ X и Y ⊂P(X). \
> • Пусть f : X →P(X) — биекция. \
> • Рассмотрим множество $Z = \{x \in X |x \notin f(x)\}$. \
> • Пусть $z = f^{−1}(Z)$. Верно ли, что $z \in Z$? \
> ▶ Если $z \in Z$, то $z \in f(z)$, откуда $z \notin Z$; \
> ▶ если $z \notin Z$, то $z \notin f(z)$, откуда $z \in Z$. \
> • В любом случае получаем противоречие.


> ### Замечание
> • Из этой теоремы следует, что не существует множества наибольшей мощности. Следовательно, нет и множества всех множеств.
> • Для конечных множеств это означает, что $2^n$ всегда больше $n$.