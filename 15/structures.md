# Структуры в matlab

Структуры - это массивы с именованными полями, которые могут хранить данные разных типов и размеров

> Structures - Arrays with named fields that can contain data of varying types and sizes

Массив структур - это тип данных, объединяющий связанные данные используя контейнеры, называемые полями. Каждое поле может содержать любой тип данных.

> A structure array is a data type that groups related data using data containers called fields. Each field can contain any type of data.

Доступ к данным в структуре осуществляется через точку: `structName.fieldName`

## Создание структур

Существует несколько способов для создания структур:

```matlab
book.title = 'Алгоритмы. Построение и анализ'
book.author = 'Томас Кормен'

book
```

Результат выполнения:

```
book = 

     title: 'Алгоритмы. Построение и анализ'
    author: 'Томас Кормен'
```

Другой способ, используя функцию struct. Результат будет таким же, как и в предыдущем примере

```matlab
book = struct('title', 'Алгоритмы. Построение и анализ', 'author', 'Томас Кормен')

book
```

Один элемент структуры не представляет интереса, учитывая возможности MATLAB по обработке массивов данных.

```matlab
books(1).title = 'Алгоритмы. Построение и анализ'
books(1).author = 'Томас Кормен'
books(1).price = 5821

books(2).title = 'Компиляторы. Принципы, технологии и инструментарий'
books(2).author = 'Альфред В. Ахо'
books(2).price = 4990

books
```

Выдаст следующий результат:

```
books = 

1x2 struct array with fields:

    title
    author
    price
```

### Слияние структур

Для слияния структур используется оператор `[]`

```matlab
struct1.a = 'first';
struct1.b = [1,2,3];

struct2.a = 'second';
struct2.b = rand(5);

combined = [struct1, struct2]

combined(2).a
```

```
combined = 

1x2 struct array with fields:

    a
    b

ans =

second
```

Слияние также можно использовать для векторов структур:
```matlab
new(1,1).a = 1;
new(1,1).b = 10;
new(1,2).a = 2;
new(1,2).b = 20;
new(2,1).a = 3;
new(2,1).b = 30;
new(2,2).a = 4;
new(2,2).b = 40;

larger = [combined; new]
```

```
larger = 

3x2 struct array with fields:

    a
    b
```

## Вложенные структуры

Общий синтаксис: `structName(index).nestedStructName(index).fieldName(indices)`

```matlab
s1 = struct('name', 'a', 'value', 3.14)
s2 = struct('name', 'b', 'value', 5)

g(1) = struct('data', 3.13, 'child', s1)
g(2) = struct('data', 'asga', 'child', s2)

g

g(2).data
g(1).child.name
```

```
g = 

1x2 struct array with fields:

    data
    child

ans =

asga


ans =

a
```