# JavaScript алгоритмы и структуры данных

[![Build Status](https://travis-ci.org/trekhleb/javascript-algorithms.svg?branch=master)](https://travis-ci.org/trekhleb/javascript-algorithms)
[![codecov](https://codecov.io/gh/trekhleb/javascript-algorithms/branch/master/graph/badge.svg)](https://codecov.io/gh/trekhleb/javascript-algorithms)

Этот репозиторий содержит примеры на JavaScript
множества популярных алгоритмов и структур данных.

Каждый алгоритм и структура данных описана в своем собственном README
со всеми связанными пояснениями и ссылками для детального изучения 
(включая ссылки на YouTube видео).

_Читайте на других языках:_
[_简体中文_](README.zh-CN.md),
[_繁體中文_](README.zh-TW.md),
[_한국어_](README.ko-KR.md),
[_日本語_](README.ja-JP.md),
[_Polski_](README.pl-PL.md),
[_Français_](README.fr-FR.md),
[_Español_](README.es-ES.md),
[_Português_](README.pt-BR.md),
[_Русский_](README.ru-RU.md)

*☝ Обратите внимание, что этот проект предназначен только для изучения и исследования, 
а **не** для использования в продакшн коде.*

## Структуры данных

Структуры данных - это способ организации и хранения данных в компьютере так, что 
к этим данным можно эффективно и быстро получить доступ и их изменить.
Если говорить более точно, то структуры данных это множество значений, связанных друг с другом, 
а также функции или операции для работы с этими данными.

`B` - Новичок, `A` - Продвинутый

* `Н` [Linked List](src/data-structures/linked-list)
* `Н` [Doubly Linked List](src/data-structures/doubly-linked-list)
* `Н` [Queue](src/data-structures/queue)
* `Н` [Stack](src/data-structures/stack)
* `Н` [Hash Table](src/data-structures/hash-table)
* `Н` [Heap](src/data-structures/heap) - max and min heap versions
* `Н` [Priority Queue](src/data-structures/priority-queue)
* `П` [Trie](src/data-structures/trie)
* `П` [Tree](src/data-structures/tree)
  * `П` [Binary Search Tree](src/data-structures/tree/binary-search-tree)
  * `П` [AVL Tree](src/data-structures/tree/avl-tree)
  * `П` [Red-Black Tree](src/data-structures/tree/red-black-tree)
  * `П` [Segment Tree](src/data-structures/tree/segment-tree) - with min/max/sum range queries examples
  * `П` [Fenwick Tree](src/data-structures/tree/fenwick-tree) (Binary Indexed Tree)
* `П` [Graph](src/data-structures/graph) (both directed and undirected)
* `П` [Disjoint Set](src/data-structures/disjoint-set)
* `П` [Bloom Filter](src/data-structures/bloom-filter)

## Алгоритмы

Алгоритм - это однозначная спецификация способа решения класса задач.
Это набор правил, которые точно определяют последовательность операций.

`Н` - Новичок, `П` - Продвинутый

### Алгоритмы по темам

* **Математические**
  * `Н` [Bit Manipulation](src/algorithms/math/bits) - set/get/update/clear bits, multiplication/division by two, make negative etc.
  * `Н` [Factorial](src/algorithms/math/factorial) 
  * `Н` [Fibonacci Number](src/algorithms/math/fibonacci) - classic and closed-form versions
  * `Н` [Primality Test](src/algorithms/math/primality-test) (trial division method)
  * `Н` [Euclidean Algorithm](src/algorithms/math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  * `Н` [Least Common Multiple](src/algorithms/math/least-common-multiple) (LCM)
  * `Н` [Sieve of Eratosthenes](src/algorithms/math/sieve-of-eratosthenes) - finding all prime numbers up to any given limit
  * `Н` [Is Power of Two](src/algorithms/math/is-power-of-two) - check if the number is power of two (naive and bitwise algorithms)
  * `Н` [Pascal's Triangle](src/algorithms/math/pascal-triangle)
  * `Н` [Complex Number](src/algorithms/math/complex-number) - complex numbers and basic operations with them
  * `Н` [Radian & Degree](src/algorithms/math/radian) - radians to degree and backwards conversion
  * `Н` [Fast Powering](src/algorithms/math/fast-powering)
  * `П` [Integer Partition](src/algorithms/math/integer-partition)
  * `П` [Square Root](src/algorithms/math/square-root) - Newton's method
  * `П` [Liu Hui π Algorithm](src/algorithms/math/liu-hui) - approximate π calculations based on N-gons
  * `П` [Discrete Fourier Transform](src/algorithms/math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up 
* **Множества**
  * `Н` [Cartesian Product](src/algorithms/sets/cartesian-product) - product of multiple sets
  * `Н` [Fisher–Yates Shuffle](src/algorithms/sets/fisher-yates) - random permutation of a finite sequence
  * `П` [Power Set](src/algorithms/sets/power-set) - all subsets of a set (bitwise and backtracking solutions)
  * `П` [Permutations](src/algorithms/sets/permutations) (with and without repetitions)
  * `П` [Combinations](src/algorithms/sets/combinations) (with and without repetitions)
  * `П` [Longest Common Subsequence](src/algorithms/sets/longest-common-subsequence) (LCS)
  * `П` [Longest Increasing Subsequence](src/algorithms/sets/longest-increasing-subsequence)
  * `П` [Shortest Common Supersequence](src/algorithms/sets/shortest-common-supersequence) (SCS)
  * `П` [Knapsack Problem](src/algorithms/sets/knapsack-problem) - "0/1" and "Unbound" ones
  * `П` [Maximum Subarray](src/algorithms/sets/maximum-subarray) - "Brute Force" and "Dynamic Programming" (Kadane's) versions
  * `П` [Combination Sum](src/algorithms/sets/combination-sum) - find all combinations that form specific sum
* **Строки**
  * `Н` [Hamming Distance](src/algorithms/string/hamming-distance) - number of positions at which the symbols are different
  * `П` [Levenshtein Distance](src/algorithms/string/levenshtein-distance) - minimum edit distance between two sequences
  * `П` [Knuth–Morris–Pratt Algorithm](src/algorithms/string/knuth-morris-pratt) (KMP Algorithm) - substring search (pattern matching)
  * `П` [Z Algorithm](src/algorithms/string/z-algorithm) - substring search (pattern matching)
  * `П` [Rabin Karp Algorithm](src/algorithms/string/rabin-karp) - substring search
  * `П` [Longest Common Substring](src/algorithms/string/longest-common-substring)
  * `П` [Regular Expression Matching](src/algorithms/string/regular-expression-matching)
* **Поиски**
  * `Н` [Linear Search](src/algorithms/search/linear-search)
  * `Н` [Jump Search](src/algorithms/search/jump-search) (or Block Search) - search in sorted array
  * `Н` [Binary Search](src/algorithms/search/binary-search) - search in sorted array
  * `Н` [Interpolation Search](src/algorithms/search/interpolation-search) - search in uniformly distributed sorted array
* **Сортировки**
  * `Н` [Bubble Sort](src/algorithms/sorting/bubble-sort)
  * `Н` [Selection Sort](src/algorithms/sorting/selection-sort)
  * `Н` [Insertion Sort](src/algorithms/sorting/insertion-sort)
  * `Н` [Heap Sort](src/algorithms/sorting/heap-sort)
  * `Н` [Merge Sort](src/algorithms/sorting/merge-sort)
  * `Н` [Quicksort](src/algorithms/sorting/quick-sort) - in-place and non-in-place implementations
  * `Н` [Shellsort](src/algorithms/sorting/shell-sort)
  * `Н` [Counting Sort](src/algorithms/sorting/counting-sort)
  * `Н` [Radix Sort](src/algorithms/sorting/radix-sort)
* **Связанные списки**
  * `Н` [Straight Traversal](src/algorithms/linked-list/traversal)
  * `Н` [Reverse Traversal](src/algorithms/linked-list/reverse-traversal)
* **Деревья**
  * `Н` [Depth-First Search](src/algorithms/tree/depth-first-search) (DFS)
  * `Н` [Breadth-First Search](src/algorithms/tree/breadth-first-search) (BFS)
* **Графы**
  * `Н` [Depth-First Search](src/algorithms/graph/depth-first-search) (DFS)
  * `Н` [Breadth-First Search](src/algorithms/graph/breadth-first-search) (BFS)
  * `Н` [Kruskal’s Algorithm](src/algorithms/graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * `П` [Dijkstra Algorithm](src/algorithms/graph/dijkstra) - finding shortest paths to all graph vertices from single vertex
  * `П` [Bellman-Ford Algorithm](src/algorithms/graph/bellman-ford) - finding shortest paths to all graph vertices from single vertex
  * `П` [Floyd-Warshall Algorithm](src/algorithms/graph/floyd-warshall) - find shortest paths between all pairs of vertices
  * `П` [Detect Cycle](src/algorithms/graph/detect-cycle) - for both directed and undirected graphs (DFS and Disjoint Set based versions)
  * `П` [Prim’s Algorithm](src/algorithms/graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * `П` [Topological Sorting](src/algorithms/graph/topological-sorting) - DFS method
  * `П` [Articulation Points](src/algorithms/graph/articulation-points) - Tarjan's algorithm (DFS based)
  * `П` [Bridges](src/algorithms/graph/bridges) - DFS based algorithm
  * `П` [Eulerian Path and Eulerian Circuit](src/algorithms/graph/eulerian-path) - Fleury's algorithm - Visit every edge exactly once
  * `П` [Hamiltonian Cycle](src/algorithms/graph/hamiltonian-cycle) - Visit every vertex exactly once
  * `П` [Strongly Connected Components](src/algorithms/graph/strongly-connected-components) - Kosaraju's algorithm
  * `П` [Travelling Salesman Problem](src/algorithms/graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
* **Криптография**
  * `Н` [Polynomial Hash](src/algorithms/cryptography/polynomial-hash) - rolling hash function based on polynomial
* **Машинное обучение**
  * `Н` [NanoNeuron](https://github.com/trekhleb/nano-neuron) - 7 simple JS functions that illustrate how machines can actually learn (forward/backward propagation)
* **Без категории**
  * `Н` [Tower of Hanoi](src/algorithms/uncategorized/hanoi-tower)
  * `Н` [Square Matrix Rotation](src/algorithms/uncategorized/square-matrix-rotation) - in-place algorithm
  * `Н` [Jump Game](src/algorithms/uncategorized/jump-game) - backtracking, dynamic programming (top-down + bottom-up) and greedy examples 
  * `Н` [Unique Paths](src/algorithms/uncategorized/unique-paths) - backtracking, dynamic programming and Pascal's Triangle based examples 
  * `Н` [Rain Terraces](src/algorithms/uncategorized/rain-terraces) - trapping rain water problem (dynamic programming and brute force versions)
  * `Н` [Recursive Staircase](src/algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top (4 solutions)
  * `П` [N-Queens Problem](src/algorithms/uncategorized/n-queens)
  * `П` [Knight's Tour](src/algorithms/uncategorized/knight-tour)

### Алгоритмы по парадигмам

Алгоритмическая парадигма — это общий метод или подход, лежащий в основе класса алгоритмов.
Это такая же абстракция над алгоритмом, как алгоритм является абстракцией компьютерной программы.

* **Brute Force** - look at all the possibilities and selects the best solution
  * `B` [Linear Search](src/algorithms/search/linear-search)
  * `B` [Rain Terraces](src/algorithms/uncategorized/rain-terraces) - trapping rain water problem
  * `B` [Recursive Staircase](src/algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top
  * `A` [Maximum Subarray](src/algorithms/sets/maximum-subarray)
  * `A` [Travelling Salesman Problem](src/algorithms/graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
  * `A` [Discrete Fourier Transform](src/algorithms/math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up
* **Greedy** - choose the best option at the current time, without any consideration for the future
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `A` [Unbound Knapsack Problem](src/algorithms/sets/knapsack-problem)
  * `A` [Dijkstra Algorithm](src/algorithms/graph/dijkstra) - finding shortest path to all graph vertices
  * `A` [Prim’s Algorithm](src/algorithms/graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * `A` [Kruskal’s Algorithm](src/algorithms/graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
* **Divide and Conquer** - divide the problem into smaller parts and then solve those parts
  * `B` [Binary Search](src/algorithms/search/binary-search)
  * `B` [Tower of Hanoi](src/algorithms/uncategorized/hanoi-tower)
  * `B` [Pascal's Triangle](src/algorithms/math/pascal-triangle)
  * `B` [Euclidean Algorithm](src/algorithms/math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  * `B` [Merge Sort](src/algorithms/sorting/merge-sort)
  * `B` [Quicksort](src/algorithms/sorting/quick-sort)
  * `B` [Tree Depth-First Search](src/algorithms/tree/depth-first-search) (DFS)
  * `B` [Graph Depth-First Search](src/algorithms/graph/depth-first-search) (DFS)
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `B` [Fast Powering](src/algorithms/math/fast-powering)
  * `A` [Permutations](src/algorithms/sets/permutations) (with and without repetitions)
  * `A` [Combinations](src/algorithms/sets/combinations) (with and without repetitions)
* **Dynamic Programming** - build up a solution using previously found sub-solutions
  * `B` [Fibonacci Number](src/algorithms/math/fibonacci)
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `B` [Unique Paths](src/algorithms/uncategorized/unique-paths)
  * `B` [Rain Terraces](src/algorithms/uncategorized/rain-terraces) - trapping rain water problem
  * `B` [Recursive Staircase](src/algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top
  * `A` [Levenshtein Distance](src/algorithms/string/levenshtein-distance) - minimum edit distance between two sequences
  * `A` [Longest Common Subsequence](src/algorithms/sets/longest-common-subsequence) (LCS)
  * `A` [Longest Common Substring](src/algorithms/string/longest-common-substring)
  * `A` [Longest Increasing Subsequence](src/algorithms/sets/longest-increasing-subsequence)
  * `A` [Shortest Common Supersequence](src/algorithms/sets/shortest-common-supersequence)
  * `A` [0/1 Knapsack Problem](src/algorithms/sets/knapsack-problem)
  * `A` [Integer Partition](src/algorithms/math/integer-partition)
  * `A` [Maximum Subarray](src/algorithms/sets/maximum-subarray)
  * `A` [Bellman-Ford Algorithm](src/algorithms/graph/bellman-ford) - finding shortest path to all graph vertices
  * `A` [Floyd-Warshall Algorithm](src/algorithms/graph/floyd-warshall) - find shortest paths between all pairs of vertices
  * `A` [Regular Expression Matching](src/algorithms/string/regular-expression-matching)
* **Backtracking** - similarly to brute force, try to generate all possible solutions, but each time you generate next solution you test
if it satisfies all conditions, and only then continue generating subsequent solutions. Otherwise, backtrack, and go on a
different path of finding a solution. Normally the DFS traversal of state-space is being used.
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `B` [Unique Paths](src/algorithms/uncategorized/unique-paths)
  * `B` [Power Set](src/algorithms/sets/power-set) - all subsets of a set
  * `A` [Hamiltonian Cycle](src/algorithms/graph/hamiltonian-cycle) - Visit every vertex exactly once
  * `A` [N-Queens Problem](src/algorithms/uncategorized/n-queens)
  * `A` [Knight's Tour](src/algorithms/uncategorized/knight-tour)
  * `A` [Combination Sum](src/algorithms/sets/combination-sum) - find all combinations that form specific sum
* **Branch & Bound** - remember the lowest-cost solution found at each stage of the backtracking
search, and use the cost of the lowest-cost solution found so far as a lower bound on the cost of
a least-cost solution to the problem, in order to discard partial solutions with costs larger than the
lowest-cost solution found so far. Normally BFS traversal in combination with DFS traversal of state-space
tree is being used.

## Как использовать этот репозиторий

**Установка всех зависимостей**
```
npm install
```

**Запуск ESLint**

Вы можете запустить проверку качества кода.

```
npm run lint
```

**Запуск всех тестов**
```
npm test
```

**Запуск тестов по имени**
```
npm test -- 'LinkedList'
```

**Песочница**

Вы можете поиграть со структурами данных и алгоритмами в файле `./src/playground/playground.js`
и написать тесты для него в `./src/playground/__test__/playground.test.js`.

Затем просто запустите следующую команду для проверки кода в песочнице на соответствие тому,
что вы задумали:

```
npm test -- 'playground'
```

## Полезная информация

### Ссылки

[▶ Data Structures and Algorithms on YouTube](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

### Нотация большое О

*Нотация большое О* используется для классификации алгоритмов по их времени выполнения или 
по росту памяти с ростом числа элементов во входных данных. На графике ниже вы можете увидеть 
наиболее частые порядки роста алгоритмов, обозначенные с помощью нотации большое О.

![Big O graphs](./assets/big-o-graph.png)

Source: [Big O Cheat Sheet](http://bigocheatsheet.com/).

Ниже приведена таблица некоторых из частоиспользуемых нотаций большого О и сравнение их производительности с ростом входных данных.

| Нотация большое О | Обработка 10 элементов | Обработка 100 элементов | Обработка 1000 элементов  |
| -------------- | ---------------------------- | ----------------------------- | ------------------------------- |
| **O(1)**       | 1                            | 1                             | 1                               |
| **O(log N)**   | 3                            | 6                             | 9                               |
| **O(N)**       | 10                           | 100                           | 1000                            |
| **O(N log N)** | 30                           | 600                           | 9000                            |
| **O(N^2)**     | 100                          | 10000                         | 1000000                         |
| **O(2^N)**     | 1024                         | 1.26e+29                      | 1.07e+301                       |
| **O(N!)**      | 3628800                      | 9.3e+157                      | 4.02e+2567                      |

### Сложность операций со структурами данных

| Структура данных        | Доступ    | Поиск     | Вставка   | Удаление  | Комментарий|
| ----------------------- | :-------: | :-------: | :-------: | :-------: | :-------- |
| **Array**               | 1         | n         | n         | n         |           |
| **Stack**               | n         | n         | 1         | 1         |           |
| **Queue**               | n         | n         | 1         | 1         |           |
| **Linked List**         | n         | n         | 1         | n         |           |
| **Hash Table**          | -         | n         | n         | n         | In case of perfect hash function costs would be O(1) |
| **Binary Search Tree**  | n         | n         | n         | n         | In case of balanced tree costs would be O(log(n)) |
| **B-Tree**              | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Red-Black Tree**      | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **AVL Tree**            | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Bloom Filter**        | -         | 1         | 1         | -         | False positives are possible while searching |

### Сложность алгоритмов сортировки массивов

| Имя                   | Лучший          | Средний             | Худший              | Память    | Устойчивость | Комментарий |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Bubble sort**       | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Insertion sort**    | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Selection sort**    | n<sup>2</sup>   | n<sup>2</sup>       | n<sup>2</sup>       | 1         | No        |           |
| **Heap sort**         | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | 1         | No        |           |
| **Merge sort**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | n         | Yes       |           |
| **Quick sort**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n<sup>2</sup>       | log(n)    | No        | Quicksort is usually done in-place with O(log(n)) stack space |
| **Shell sort**        | n&nbsp;log(n)   | depends on gap sequence   | n&nbsp;(log(n))<sup>2</sup>  | 1         | No         |           |
| **Counting sort**     | n + r           | n + r               | n + r               | n + r     | Yes       | r - biggest number in array |
| **Radix sort**        | n * k           | n * k               | n * k               | n + k     | Yes       | k - length of longest key |
