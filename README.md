# There is all my code for 2nd semester of 1st year

## each folder has nested folder `code_data` - there is code, data and MakeFile

## how to run MakeFile?

+ build and run
```bash
$ make -f MakeFile
```
+ remove files like `*.o` and executable file `full`
```bash
$ make -f MakeFile clean
```

## conditions
#### lab20 - ??
    без варианта, нужно было просто потыкать команды
#### lab21 - 16:
    удаление файлов с указанным префиксом и максимальными размерами, 
    пока общий размер остающихся файлов не станет меньше заданного числа 
#### lab22 - стр 347-348:
    затехать странички из учебника Кудрявцева по матану
#### lab23 - 15:
    проверить, находятся ли все листья двоичного дерева на одном уровне (я делал для BST)
#### lab24 - 35:   
    подсчитать количество операндов (переменных и констант) в выражении 
    (тут по сути просто подсчет кол-ва листьев двоичного дерева)
#### lab25_26 - 4, 3
    процедура - конкатенация двух списков
    метод - быстрая сортировка Хоара (у меня тут рекурсивный вариант реализации)
    в lab25 стоит задача сделать MakeFile для lab26
#### cp6 - (12-21), 18:
    содержимое файл - информация об успеваемости студентов данной группы по всем предметам:
                      фамилия, инициалы, пол, номер группы, отметки по экзаменам и зачетам
    действие - выяснить, в какой группе разность между максимальным
               и минимальным средним баллом студентов максимальна
#### cp7 - 2, 8:
    вариант размещения матрицы - один вектор
    задача - 1) вычислить произведение двух разреженных матриц
             2) проверить, является ли полученная матрица диагональной  
#### cp8 - on vector, 3, 2, 8: 
    реализация списка - на векторе
    тип элементов списка - перечислимый (enum) тип
    вид списка - линейный однонаправленный
    действие - дополнить список копиями заданного значения до указанной длины k списка.
               если в списке уже имеется не менее k элементов, то не менять его
#### cp9 - 4, 1: 
    метод сортировки - Шейкер-сортировка
    структура таблица:
        тип ключа - целый
        длина ключа в байтах - 8 (long int)
        хранение данных и ключей - вместе
        число элементов таблицы 8~12
        
#### курсач по дискретной математике - 8:
    задача - реализовать алгоритм Дейкстры поиска 
             кратчайших маршрутов из каждой вершины графа в каждую
    язык - c++
    платформа - графоид (папка с этой штукой тоже здесь есть)
    примечание: только main_win.exe подходит для графоида
    
#### mini_exam1_python_script - ??:
    задание - решить задачу из lab21 на языке python
    
#### mini_exam2_leetcode_C - 1689:
    задача - Partitioning Into Minimum Number Of Deci-Binary Numbers
    описание алгоритма - найти максимальную цифру в строке
    пример теста:
        Input: n = "32"
        Output: 3
        Explanation: 10 + 11 + 11 = 32










