------- Контрольная работа -----------

Морозов Александр Олегович


Поэтапный план выполнения задания
1 - Создать репозиторий в Гит, сопрячь его с файлами на компе, все проверить
2 - написать план выполнения в READMe
3 - Составить блоксхему программы целиком
4 - Написать саму программу согласно Блоксхеме.
5 - Дать описание работы программы по шагам.


Расположение в файлах
Програмный код задания распологается в папке control_work -> Файл Program.cs
Блок-Cхема программы расположена отдельный файлом "блок_схема алгоритма.jpg"


Описание програмного решения
Для решения основного задания я выбрал тот вариант программы, при котором пользователь задает массив слов с консоли,
тк по моему мнению это самый эффективный способ для тестирования. Программа состоит из 6 частей, между каждой составлен небольшой отделяющий коментарий.

В первой части программы мы выводим сообщение пользователю о необходимости ввода числа слов в изначальном массиве.

Во второй части мы создаем Первый массив, с количеством слов которое пользователь ввел ранее, а затем его заполняем.

В третьей части используя проверку на "пустое заполнение" мы принимаем поочередно значения для каждлого "слова" в массиве.

В четвертой части программы мы создаем дополнительный счетчик со значением ноль для слов меньше 3 символов, а также сам второй массив строк для отсортированных слов, при том длина второго массива строк равна длине первого массива строк.

В пятой части с помощью for мы сортируем первый массив строк и слова с длинной в два или меньше символов мы добавляем по порядку во второй массив строк, при том после каждого прохождения цикла добавления мы прибавляем единицу к числу счетчика второга массива строк, созданного ранее.

В шестой части программы мы выводим второй массив строк с отсортированными словами длинной меньше или равной трем символам. по скольку слова в массив мы записывали по порядку и при том их число отображенно в дополнительном счетчике
второго массива, то мы выводим второй массив строк до тех пор, пока счетчик цикла вывода меньше дополнительного счетчика второго массива строк. (i < secondArrayIndex)

Таким образом, в заключение, программа выполняет поставленное задание а также имеет дополнительный функционал для ввода первого массива с консоли и проверки введенных слов а в случае чего дает возможность ввести слово заново, без вылета программы, что делает ее удобной для тестирования.
