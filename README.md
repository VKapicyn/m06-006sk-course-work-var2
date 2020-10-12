# m06-006sk-course-work-var2
Вариант №2. Сравнение эффективности оптимизации «по Дарвину» и «по Ламарку» для методов Монте-Карло моделирования случайных блужданий.

## Часть 1. Сравнение на графе

**Актуальные вопросы:**
1) какой граф рассмтариваем. Есть ли какие-то требования, кроме 1024 узлов?
2) рассматриваем ли вариант, что нет пути от А до Б? То есть граф несвязный
3) как проводим селекцию? По оставшемуся расстоянию до нужной вершины? По факту прихода/не прихода в нужную вершину?
4) как сравнить эффективность алгоритмов? По количеству итераций до результата?

**Инструменты.**
Рисуем граф: 
основная библиотека - https://towardsdatascience.com/newbies-guide-to-python-igraph-4e51689c35b4
запасная библиотека - https://networkx.github.io/documentation/stable/tutorial.html
базовая инфа о графах для новичков в Python - https://habr.com/ru/post/112421/

Генетический алгоритм:
введение в генетические алгоритмы (с примерами кода) - https://habr.com/ru/post/498914/

Муравьиный алгоритм:

## Часть 2. Сравнение в трёхмерном пространстве

**Актуальные вопросы:**
1) всегда одинаковая длина прогона?
2) С какой погрешностью мы определяем, что оказались в нужной точке?

**Для ознакомления:**
просто про Марковские процессы: https://www.youtube.com/watch?v=t8JQywTdW7o&ab_channel=selfedu
обзор на пакеты, реализующие Марковские процессы: https://martin-thoma.com/python-markov-chain-packages/

Предварительный подбор пакетов, которые, наверное, могут подойти:
Марковские процессы - https://github.com/sawcordwell/pymdptoolbox
Генетический алгоритм - https://pypi.org/project/geneticalgorithm/
Муравьиный алгоритм:
https://pypi.org/project/ACO-Pants/
https://github.com/pjmattingly/ant-colony-optimization
