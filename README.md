ЦЕЛЬ
Создать программу, в которой бы визуализировались результаты преобразований и ЦОС сигналов.






Как добавить компиляторы и ninja для запука Qt 6 на ноутбуке:

1.Заходим во вкладку «Проекты» на левой боковой панели проекта

2. В строках на вкладке Initial Configuration

CMAKE_CXX_COMPILER          D:\Qt 6\Qt6.7.2-tools win\Qt\Tools\mingw1120_64\bin\g++.exe

CMAKE_C_COMPILER               D:\Qt 6\Qt6.7.2-tools-win\Qt\Tools\mingw1120_64\bin\gcc.exe

3. Далее заходим во вкладку справа Current Configuration и нажимаем галочку Дополнительно, чтобы появилась строка
CMAKE_MAKE_PROGRAM
И вставляем туда путь к Ninja D:/Qt 6/Qt6.7.2-tools-win/Qt/Tools/Ninja/ninja.exe
4. После этого на вкладке Current Configuration внизу нажимаем на кнопку Запустить CMake

Готово 😊
