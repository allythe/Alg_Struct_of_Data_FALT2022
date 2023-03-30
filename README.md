place, where algorithms live 🐝  

🐌 [ссылки на презентации](https://drive.google.com/drive/folders/1QBCvxZU1U_fdN9A6kRGHpI7rfHfRxNjs?sort=13&direction=a
) (прошло-прошлогодние)

## 🦉 Программа экзамена 1 курс, 2 семестр

### Введение.
- 0.1.1. Определение алгоритма. Примеры простых алгоритмов: вычисление числа Фибоначчи, проверка числа на простоту, быстрое возведение в степень.
- 0.1.2. Асимптотические обозначения, работа с ними.
- 0.1.3. Определение структуры данных, абстрактного типа данных (интерфейса).
- 0.1.4. Массив. Линейный поиск. Бинарный поиск.

### Тема 1. Базовые структуры данных
- 1.1.1. Динамический массив.
- 1.1.2. Амортизационный анализ. Амортизированное (учетное) время добавления элемента в динамический массив.
- 1.1.3. Двусвязный и односвязный список. Операции. Объединение списков.
- 1.1.4. Стек.
- 1.1.5. Очередь.
- 1.1.6. Дек.
- 1.1.7. Хранение стека, очереди и дека в массиве. Циклическая очередь в массиве.
- 1.1.8. Хранение стека, очереди и дека в списке.
- 1.1.9. Поддержка минимума в стеке.
- 1.1.10. Представление очереди в виде двух стеков. Время извлечения элемента.
- 1.1.11. Поддержка минимума в очереди.
- 1.1.12. Двоичная куча. АТД “Очередь с приоритетом”.

### Тема 2. Сортировки и порядковые статистики.
- 2.1.1. Формулировка задачи. Устойчивость, локальность.
- 2.1.2. Квадратичные сортировки: сортировка вставками, выбором.
- 2.1.3. Сортировка слиянием.
- 2.1.4. Сортировка с помощью кучи.
- 2.2.1. Слияние K отсортированных массивов с помощью кучи.
- 2.2.2. Нижняя оценка времени работы для сортировок сравнением.
- 2.2.3. Быстрая сортировка. Выбор опорного элемента. Доказательство среднего времени работы.
- 2.2.4. Сортировка подсчетом. Карманная сортировка.
- 2.3.1. Поразрядная сортировка.
- 2.3.2. MSD, LSD. Сортировка строк.
- 2.3.3. Поиск k-ой порядковой статистики методом QuickSelect.
- 2.3.4. Поиск k-ой порядковой статистики за линейное время.

### Тема 3. Деревья поиска.
- 3.1.1. Определение дерева, дерева с корнем. Высота дерева, родительские, дочерние узлы, листья.Количество ребер.
- 3.1.2. Обходы в глубину. pre-order, post-order и in-order для бинарных деревьев.
- 3.1.3. Обход в ширину.
- 3.1.4. Дерево поиска.Поиск ключа, вставка, удаление.
- 3.2.1. Необходимость балансировки. Три типа самобалансирующихся деревьев.
- 3.2.2. Декартово дерево. Оценка средней высоты декартового дерева при случайных приоритетах (без доказательства).
- 3.2.3. Построение за O(n), если ключи упорядочены.
- 3.2.4. Основные операции над декартовым деревом.
- 3.2.5. АВЛ-дерево. Вращения.
- 3.2.6. Оценка высоты АВЛ-дерева.
- 3.2.7. Операции вставки и удаления в АВЛ-дереве.
- 3.3.1. Красно-черное дерево.
- 3.3.2. Оценка высоты красно-черного дерева.
- 3.3.3. Операции вставки и удаления в красно-черном дереве.
- 3.4.1. Сплей-дерево. Операция Splay.
- 3.4.2. Поиск, вставка, удаление в сплей-дереве.
- 3.4.3. Учетная оценка операций в сплей-дереве.
- 3.4.4. B-деревья.

### Тема 4. Хеш-таблицы.
- 4.1.1. Хеш-функции. Остаток от деления, мультипликативная.
- 4.1.2. Деление многочленов - CRC.
- 4.1.3. Обзор криптографических хеш-функций. CRC*, MD*, SHA*.
- 4.1.4. Полиномиальная. Ее использование для строк. Метод Горнера для уменьшения количества операций умножения при ее вычислении.
- 4.1.5. Хеш-таблицы. Понятие коллизии.
- 4.2.1. Метод цепочек (открытое хеширование).
- 4.2.2. Метод прямой адресации (закрытое хеширование).
- 4.2.3. Линейное пробирование. Проблема кластеризации.
- 4.2.4. Квадратичное пробирование.
- 4.2.5. Двойное хеширование.

### Тема 5. Жадные алгоритмы и Динамическое программирование.
- 5.1.1. Общая идея жадных алгоритмов.
- 5.1.2. Задача о рюкзаке.
- 5.1.3. Общая идея последовательного вычисления зависимых величин. Идея введения подзадач (декомпозиции) для решения поставленной задачи. Восходящее ДП. Нисходящее ДП, кэширование результатов.
- 5.1.4. Вычисление чисел Фибоначчи. Нахождение количества последовательностей нулей и единиц длины n, в которых не встречаются две идущие подряд единицы.
- 5.1.5. Нахождение наибольшей возрастающей подпоследовательности за O(N2) и за O(N log N).
- 5.1.6. Количество способов разложить число N на слагаемые.
- 5.1.7. Количество способов разложить число N на различные слагаемые.
- 5.1.8. Нахождение наибольшей общей подпоследовательности.
- 5.1.9. Методы восстановления ответа в задачах динамического программирования.
- 5.1.10. Расстояние Левенштейна.


## 🦉 Программа экзамена 2 курс, 3 семестр
### 🦭 1. Обходы графа. 
- 1.1. Ориентированный граф, псевдограф. Неориентированный граф,
псевдограф. Связность в неор. графе, компоненты связности. Слабая и сильная связность в ор. графе. Компоненты слабой, сильной связности.
- 1.2. Обход в глубину. Цвета вершин. Времена входа и выхода. Лемма о белых путях(с доказательством).
- 1.3. Проверка связности неориентированного графа. Поиск цикла в неориентированном и ориентированном графе. Топологическая сортировка.
- 1.4. Нахождение компонент сильной связности. Алгоритм Косарайю с доказательством корректности(концепция). Алгоритм Тарьяна без доказательства корректности.
- 1.5. Компоненты реберной двусвязности. Мосты. Поиск мостов.
- 1.6. Компоненты вершинной двусвязности. Точки сочленения. Поиск точек
сочленения.
- 1.7. Волновой алгоритм. Обход в ширину (применение очереди в
волновом алгоритме).
- 1.8. Критерий существования Эйлерова пути и цикла в ориентированном
и неориентированном графе. Поиск эйлерова пути и цикла.


### 🦔 2. Планарность графа
- 2.1. Формула Эйлера. Теорема Портнягина-Куратовского. Теорема Вагнера.
- 2.2. Гамма алгоритм. Контактная вершина.
- 2.3. Теорема о корректности Гамма алгоритма. Асимптотика алгоритма.


### 🐡 3. Кратчайшие пути во взвешенном графе.
- 3.1. Алгоритм Дейкстры. Доказательство корректности.
Оценка времени работы. Дерево кратчайших путей.
- 3.2. Потенциалы. Условие применимости алгоритма Дейкстры для
измененных длин ребер. Потенциал π(v) = ρ(v, t).) = ρ(v) = ρ(v, t)., t).
- 3.3. Алгоритм A*. Условие монотонности на эвристику. Примеры
эвристик.
- 3.4. Алгоритм Форда-Беллмана. Хранение в матрице: Dv) = ρ(v, t).k равно
длине кратчайшего пути до вершины v) = ρ(v, t). за ровно k ребер (не более k ребер). Доказательство корректности. Оценка времени работы.
- 3.5. Восстановление пути. Детектирование цикла отрицательного веса. Поиск самого цикла.
- 3.6. Нахождение кратчайших путей с учетом циклов отрицательного веса с помощью алгоритма Форда-Беллмана.
- 3.7. Алгоритм Флойда. Доказательство (концепция). Восстановление пути.
- 3.8. Нахождение цикла отрицательного веса с помощью алгоритма Флойда. 
- 3.9. Алгоритм Джонсона. Оценка времени работы 


### 🦚 4. Остовные деревья.
- 4.1. Остовное дерево. Построение с помощью обхода в глубину и в
ширину.
- 4.2. Определение минимального остовного дерева(MST).
- 4.3.  Определение безопасного ребра. Лемма о безопасном ребре. Доказательство леммы.
- 4.4. Алгоритм Прима. Аналогия с алгоритмом Дейкстры. Доказательство 
корректности с помощью леммы о безопасном ребре. 
- 4.5. Оценка времени работы алгоритма Прима для различных реализаций очереди с приоритетом:
бинарная куча, Фибоначчиева куча (последнее без доказательства).
- 4.6. Алгоритм Крускала. Доказательство корректности. Оценка времени
работы.
- 4.7. Система непересекающихся множеств. Эвристика потенциалов (без
доказательства). Эвристика сжатия пути (без доказательства). Почти
константное время работы (без доказательства).
- 4.8. Алгоритм Борувки. Доказательство. Оценка времени работы.
- 4.9. Приближение решения задачи коммивояжера с помощью
MST.


### 🐞 5. Потоки в сетях.
- 5.1. Определение сети. Определение потока. Физический смысл.
Аналогия с законами Кирхгофа. 
- 5.2. Определение разреза. Понятия потока через разрез. Доказательство
факта, что поток через любой разрез одинаковый.
- 5.3. Понятие остаточной сети. Понятие дополняющего пути.
Необходимость отсутствия дополняющего пути для максимальности
потока.
- 5.4. Теорема Форда-Фалкерсона.
- 5.5. Алгоритм Форда-Фалкерсона. Поиск минимального разреза. Пример
целочисленной сети, в котором алгоритм работает долго.
- 5.6. Алгоритм Эдмондса-Карпа. Доказательство, что кратчайшее
расстояние в остаточной сети не уменьшается.
- 5.7. Общая оценка времени работы алгоритма Эдмондса-Карпа. (не
строго)
- 5.8. Слоистая сеть. Алгоритм Диница. Оценка времени работы (без
доказательства).


### 🦎 6. RMQ. Sparse-table, дерево отрезков. LCA. Декартово дерево по неявному ключу.
- 6.1. RSQ и RMQ. Sparse-table.
- 6.2. Дерево отрезков. Обработка запросов от листьев. Обработка
запросов от корня.
- 6.3. Дерево отрезков. Изменение значения в массиве, обновление
дерева отрезков. Множественные операции.
- 6.4. LCA. Метод двоичного подъёма.
- 6.5. Декартово дерево по неявному ключу. Интерфейс быстрого массива:
Доступ к элементу в позиции i, Вставка элемента в позицию i, Удаление элемента из позиции i, Конкатенация двух массивов, разделение массива на два.

