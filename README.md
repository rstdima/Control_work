###**Контрольная работа**
###**Задача:**
> Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Примеры:**
1. **[“Hello”, “2”, “world”, “:-)”]** → **[“2”, “:-)”]**
2. **[“1234”, “1567”, “-2”, “computer science”]** → **[“-2”]**
3. **[“Russia”, “Denmark”, “Kazan”]** → **[]**


####**Алгоритм решения**

Объявляем два массива: первый массив и вторый такой же длины.
Создадим переменную **count**, для записи значения из первого массива во второй.
Решаем методом, в котором цикл равен длине массива, внутри цикла  проверяем условие **(array1[i].Length <= 3)** если условие верно, эллемент первого массива записываем в переменную **count** элемент второго массива. 
 После того как мы прошлись по циклу увеличиваем нашу переменную (счетчик) **count** на **1**
 После прохода, возвращаемся к циклу, **for (int i = 0; i < array1.Length; i++)**  наша **i - увеличиваеться на 1**.

 + Блок-хема расположена в папке **Block_scheme**

 _Работу выполнил Ермачков Д.В._