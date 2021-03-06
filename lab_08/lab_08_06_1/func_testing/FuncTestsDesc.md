# Тесты для лабораторной работы №8

### Входные данные
* `int n` - ***количество элементов*** в динамическом массиве
* ***Элементы*** динамического массива
* `int p` - ***номер позиции***, на которое надо вставить число *μ₂*
 
### Выходные данные
* Вывод ***динамического массива***, либо ***сообщение*** об ошибке

### Тесты
#### Негативные тесты
* [Тест №1](in_01.txt) - вместо числа `n` вводится *символ*
* [Тест №2](in_02.txt) - число `n` *меньше 2* (массив должен содержать хотя *2* элемента)
* [Тест №3](in_03.txt) - вместо очередного *элемента* вводится символ
* [Тест №4](in_04.txt) - после первой обработки массива, массив становится *пустым* (`n = 2`)
* [Тест №5](in_05.txt) - вместо числа `p` вводится *символ*
* [Тест №6](in_06.txt) - число `p` *отрицательно*
* [Тест №7](in_07.txt) - число `p` *превышает* размер массива после первой обработки
* [Тест №8](in_08.txt) - память под динамический массив не выделена

#### Позитивные тесты
* [Тест №9](in_09.txt) - *обычный* тест
* [Тест №10](in_10.txt) - число `p` равно *0*
* [Тест №11](in_11.txt) - число `p` равно *размеру массива - 1*
* [Тест №12](in_12.txt) - массив состоит из *одинаковых* элементов 
* [Тест №13](in_13.txt) - в массиве присутствует два элемента, *модуль разности* коих со средним арифметическим (μ₁) *одинаков* и *максимален* среди всех элементов массива
* [Тест №14](in_14.txt) - после первой обработки массива в нем присутствует *два* одинаковых максимальных элемента
