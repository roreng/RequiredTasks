# Required Tasks
Образовательный репорзиторий студента. Не несет научно-познавательного характера и не является примером к исполнению. Задания предназначеные для получения автомата.
## Список обязательных к исполнению 16 задач:
<b>1. Решение квадратных уравнений:</b><br>
Дано уравнение вида: ax^2 + bx + с. Программа считывает вещественные коэффициенты а, b, c и выводит корни. Если корней нет, выводит сообщение об этом.
<br><br><b>2. Калькулятор:</b><br>
Программа считывает два целых числа и символ операции (один из * / % + -), затем выводит результат.
<br><br><b>3. Часы:</b><br>
Даны числа h и m, где h - количество часов, m - количество минут некоторого момента времени. Найдите угол между часовой и минутной стрелками в этот момент времени.
<br><br><b>4. Треугольник из символов :</b><br>
Программа считывает количество линий и выводит в консоль треугольник.
<br><br><b>5.  Наибольший и наименьший элемент в массиве:</b><br>
На вход программы подается массив целых чисел: сначала размер массива, затем его элементы. 
Программа выводит наибольший и наименьший элемент в массиве.
<br><br><b>6. Соседние элементы с минимальной суммой:</b><br>
На вход программы подается массив целых чисел: сначала размер массива, затем его элементы. 
Программа выводит два соседних элемента массива сумма которых минимальна.
<br><br><b>7.  Умножение матриц (-):</b><br>
Пользователь вводит две матрицы размера 3x3, вывести результат умножения этих матриц.
<br><br><b>8.  Поворот матрицы: (-)</b><br>
Пользователь вводит матрицу размера 3x3. Сформировать новую матрицу, полученную из исходной путем поворота относительно центра на 90 градусов по часовой стрелке.
<br>Пример:
<br>0 1 2 → 6 3 0
<br>3 4 5 → 7 4 1
<br>6 7 8 → 8 5 2
<br><br><b>9. Блэкджек: (-)</b><br>
Программа выводит текущий набор карт игрока (строку из символов J, K, Q, A и цифр), количество очков, затем считывает действие игрока: взять еще карту или остановиться. Если игрок решил остановиться программа рассчитывает количество очков у крупье и выводит результаты.
Считаем, что колода карт бесконечна, каждый раз может выпасть карта от 2 до туза. Картинки дают 10 очков, туз - 11, остальные по номиналу.
<br><br><b>10. Поиск количества вхождений заданного символа в строку: (-)</b><br>
Программа считывает строку до нажатия клавиши «Enter», затем считывает искомый символ и выводит количество вхождений этого символа в введенную ранее строку.
<br><br><b>11. Сортировка массива строк по алфавиту: (-)</b><br>
Написать функцию сортировки массива строк по алфавиту: 
<br>
```
void sort(char **array, size_t arraySize);
```
В мейне считать массив строк, передать его в функцию и вывести результат.
<br><br><b>12.  Удаление лишних пробелов: (-)</b><br>
Написать функцию, принимающую строку и возвращающую копию этой строки, в которой все серии подряд идущих пробелов заменены на одиночные пробелы. Крайние пробелы в строке удалить. В мейне считать строку, передать ее в функцию и вывести результат.
<br><br><b>13. Вектор:</b><br>
Реализовать модуль для работы с динамическим массивом.
<br>Модуль должен реализовывать все указанные в примере хедера функции.
<br>В мейне привести пример использования каждой функции.
<br>Программа должна состоять из трех файлов и собираться с помощью make.
<br><br><b>14. Менеджер контактов:</b><br>
Слишком большое описание))
<br><br><b>15. Модуль работы с файлами: (-)</b><br>
Реализовать модуль для работы с файлами.
<br>Функции модуля принимают первым аргументом указатель на FILE.
<br>Модуль должен содержать следующие функции:
<br>- Вывести файл в консоль, печатая номера строк.
<br>- Дописать указанную строку в конец файла.
<br>- Вывести строки (с их номерами), в которых есть указанная подстрока, причем саму подстроку вывести в верхнем регистре.
<br>- Перезаписать файл, удалив строку с указанным номером.
<br>- Перезаписать файл, вставив указанную строку перед строкой с указанным номером.
<br>В мейне привести пример использования каждой функции. Программа должна состоять из трех файлов и собираться с помощью make.
<br><br><b>16. Модуль комплексных чисел: (-)</b><br>
Реализовать модуль для работы с комплексными числами
<br>Модуль должен содержать следующие функции:
<br>- Сложение
<br>- Умножение 
<br>- Деление
<br>- Получение модуля числа 
<br>- Получение аргумента числа 
<br>- Получение сопряженного числа 
<br>- Вывод в алгебраической форме
<br>- Вывод в тригонометрической форме
<br>- Вывод в показательной форме
<br><br>В мейне привести пример использования каждой функции.
<br>Программа должна состоять из трех файлов и собираться с помощью make.
