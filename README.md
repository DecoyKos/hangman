Популярная игра “Виселица”

КОНСОЛЬНАЯ ИГРА “Виселица”(https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0)

ЗАПУСК ПРОГРАММЫ:
1. В консоли перейти в папку с файлом с помощью команды cd (cd <Путь до папки>)
2. В командной строке прописать ruby main.rb
3. Готово! Вы восхитительны!


ПРАВИЛА:
Компьютер загадывает слово — изначально все буквы слова неизвестны.
Чертами отмечены места для букв, также выводится виселица с петлёй.

Согласно традиции русских лингвистических игр слово - имя существительное нарицательное в именительном падеже единственного числа, либо множественного числа при отсутствии у слова формы единственного числа.

Пользователь пишет букву, которая может входить в это слово.
Если такая буква есть в слове, то компьютер пишет её вместо соответствующих этой букве чертами — столько раз, сколько она встречается в слове.
Если такой буквы нет, то к виселице добавляется круг в петле, изображающий голову.
Второй игрок продолжает отгадывать буквы до тех пор, пока не отгадает всё слово.
За каждый неправильный ответ первый игрок добавляет одну часть туловища к виселице (Всего их 8).

Если туловище в виселице нарисовано полностью(т.е. пользователь допустил ошибки 8 раз), то игрок проигрывает, считается повешенным.
Если пользователю удаётся угадать слово, он выигрывает.

ДОБАВЛЕНИЕ НОВЫХ СЛОВ:
Для добавления новых слов в игру Вам нужно зайти в папку “data” и в этой папке зайти в файл “words.txt”. В файле с новой строки написать новое слово.

