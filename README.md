Для тестирования на Linux в терминале:
g++ -o lw2 lw2.cpp
./lw2

Через другой терминал:
Или
telnet localhost 11111
Далее любые сообщения посылаем.

Или 
посылаем сигнал
сначала узнаем <PID>: ps aux | grep lw2
Заетм:
kill -SIGHUP <PID>

Или и посылание сообщений и посылание сигнала только ещё третий терминал.

Завершить процесс: kill -9 <PID>
