# controlwork
Описание алгоритма работы программы
По условиям задания, мы можем задать массив из строк вручную на старте выполнения алгоритма (что мы и сделали - [ "hello", "2", "world", ":-)", "1234", "1567", "Rus", "-2", "computer science", "Russia", "Denmark", "Kazan", "GB", "GBU" ]).

Для реализации программы мы используем несколько методов, а именно:

Метод ArrayCheck - он позволяет вычислить количество строк, по условию задания, длина которых не превышает 3 символа;
Инициализируем переменную count, равную 0. В неё мы будем записывать количество строк, длина которых 3 символа и меньше.
В цикле for проходимся по каждой строке массива. На каждой итерации сверяем длину строки - если условие (меньше либо равно трём символам) соблюдается, инкрементируем count и инкрементируем i (счётчик цикла). Если длина больше трёх, инкрементируем только счётчик цикла (i++).

Метод FillResultArray - позволяет сформировать массив, состоящий из строк, длина которых удовлетворяет условию задания.
В цикле for проходимся по каждой строке массива. На каждой итерации сверяем длину строки. Если длина строки удовлетворяет условию задания, в текущий массив записывается данная строку, декрементируем count и инкрементируем i. Если условие не выполняется, инкрементируем i.
Декрементировать count необходимо для правильного заполнения массива.

Метод PrintArray - позволяет вывести результат на экран.
