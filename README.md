# Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

## Алгоритм решения задачи:
1. Объявления массивов: *array1* (оригинальный) и *array2* (новый)
2. Объявляется метод, в котором цикл имеет ту же длину, что и массив 
3. В цикле осуществляется проверка условия (array1[i].Length <= 3)
4. Если условие выполняется, то элемент первого массива заносится в *count* элемент второго массива. После присвоения переменная *count* увеличивается на 1 и возвращается к циклу *for* в котором i увеличивается на 1 соответственно.
5. Цикл работает, пока выполяется условие, после чего осуществляется вывод нового массива.

