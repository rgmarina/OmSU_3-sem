## Лабраторная работа №4

### Задание 4.1:

### Стек минимумов
Сделать стек на основе односвязного списка, у которого трудоемкость взятие минимума, вставка в стек и удаление из него за O(1).

Связный список надо написать самим.

#### Операции:

- вставить в конец стека
- удалить последний элемент стека
- выдать минимальный элемент в стеке

#### Входные данные:
На вход программы подаются команды, их количество не превышает 100-000. В каждой строке находится одна из команд:

- push k — положить число k в стек (тип данных k-int).
- pop k — убрать последний элемент в стеке.
- top - выдать последний элемент в стеке.
- min - выдать текущий минимум в стеке.

Гарантируется, что некорректные команды подаваться НЕ будут.

#### Выходные данные:
Вывести результат выполнения команд top и min в консоль.


### Задание 4.2:

### Очередь с приоритетом на основе Кучи
Разработать структуру данных Очередь, выполняющую следующие операции:

- Вставить в очередь за O(log(n)).
- Извлечь максимальный элемент O(log(n)).
- Увеличить i-ый элемент на v.


Все операции вставки в очередь вводятся по очереди и нумеруются с 1.

При извлечнении элемента из очереди, нужно вывести в стандартый поток вывода сам элемент и номер операции, когда его добавили.

То есть в структуре данных надо хранить само значение элемента и номер операции, когда его добавили.

#### Входные данные:
На вход программы подаются команды, их количество не превышает 100-000. В каждой строке находится одна из команд:

- enqueue k — вставить в очередь число k.
- dequeue_max — извлечь из очереди максимальный элемент.
- inc i v - найти элемент вставленныей на i-ой операции и увеличить его на v. Если элемента уже нет, то ничего не делать.

Тип данных k, v — int, i — unsigned int.

Гарантируется, что некорректные команды подаваться НЕ будут.

#### Выходные данные:
Команда dequeue-max печатает в консоль номер операции i, когда элемент был вставлен, и сам элемент k.

Если очередь пустая, то печатаем *.
