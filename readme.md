## 1 решение:
Вводятся два массива: первый и вторый, который равен длине первого. 
Вводится метод, в котором цикл соразмерный длине массива. Внутри цикла проверка условия ( <=3 ), 

если да элемент первого массива заносится в count элемент второго массива. Переменная count, чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так далее.



## 2 решение:

Пользователь вводит массив, и присваивается переменная stroka. Далее Вводится локальная переменная М,
 где применяется метод split, который разбивает строку на подстроки с разделителем [ ]. 
Вводится переменная result, куда записывается чсило объектов переменной М. Вводится переменная RealSize, которой присваивается 0.
Применяем метод foreach, который заходит в каждый разбитый объект массива М и проверяет его длину, если длина элемента массива больше, либо равна 3, то вывводит элемент в консоль, если нет , то идет дальше по всему массиву. 