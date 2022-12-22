**hw_final**

Задача: Написать программу, которая из имеющегося массива
строк формирует новый массив из строк, длина которых меньше,
либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры,
либо задать на старте выполнения алгоритма. При решении не рекомендуется
пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

Для решения задачи была составлена блок-схема.png
Для сортировки массива и выделения в нем элементов, длина которых <= 3, используется цикл for. 
Для выделения отобранных элементов используется еще один цикл, в котором элементы проиндексированы символом j.
Данная конструкция обернута методом void, которому присвоено имя NewArray. 
Для печати массива использован цикл for, который представлен в виде метода void, с именем Printaray.
