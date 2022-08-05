# timed-printer

Необходимо реализовать модуль ядра Linux и программу для задания параметров модуля.

## Модуль ядра Linux.
Модуль ядра Linux, при загрузке в ядро, должен записывать константные строки "Hello from kernel module" в общий файл. Строки должны дописываться в конец этого файла через определенный период по таймеру.

## Программа задания параметров модуля.
В программе должна быть реализована возможность задать имя файла, в который модуль ядра будет записывать строки, а также период времени срабатывания для таймера в секундах.

## Требования к присылаемым решениям.
- задание должно быть передано в zip архиве
- модуль ядра Linux и программа должны находиться в разных папках
- исходный код должен компилироваться средствами make (для модуля должны быть заданы цели: all, clean, load, unload)
- модуль ядра должен работать без падений и сообщений oops в файле логирования
- модуль ядра должен быть реализован для ядра Linux версии 5.10
