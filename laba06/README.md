## Лабраторная работа №6

### Задание 6.1:

### Приближенный поиск
Дан упорядоченный по возрастанию массив чисел. Дан второй массив чисел — запросы. Для каждого запроса необходимо вывести число из первого массива наиболее близкое к запрашиваемому.


#### Входные данные:
В первой строке целое число n — количество элементов в массиве. Во второй строке n целых чисел — элементов массива. В третьей строке число m — количество запросов. В четвертой строке m целых числе — запросы.

#### Выходные данные:
На выходе m чисел через пробел — результаты выполнения запросов.


### Задание 6.2:

### Дипломы
Дано N одинаковых дипломов высотой h и шириной w. Нужно найти сторону M минимально возможного квадратного ящика, в который можно будет разложить все дипломы.

Дипломы нельзя вращать и складывать друг на друга.

Алгоритм должен использовать бинарный поиск.

#### Входные данные:
На входе 3 целых числа: n w h, где 1≤n,w,h≤10^9

#### Выходные данные:
На выходе одно целое число — длина стороны минимального квадратного ящика, в который можно расположить все дипломы.

### Задание 6.3:

### Решение уравнения
Найдите такое число x, что (x^2)-x+sqrt(x)=a, с точностью не менее 6 знаков после точки.

Алгоритм должен найти корни уравнения методом динарного поиска для последовательного приближения, до тех пор, пока не будет достигнута требуемая точность.

#### Входные данные:
Вещественное число 1.0≤a≤100

#### Выходные данные:
Вещественное число x, удовлетворяющее уравнению.