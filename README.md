# Infinite-Bomber-termux


# как установить (RU)

$ apt install git

$ git clone https://github.com/SenTDI/Infinite-Bomber-android

$ cd Infinite-Bomber-android

$ cd (директория с вашим процессором(либо С тор или не с ним) К примеру $ cd Infinite-Bomber-arm64-without-tor (-without-tor без тор) (arm64 разрядность вашего процессора)

$ chmod 777 infinite-bomber

$ ./infinite-bomber

# Информация (RU)
Для работы программы необходим доступ в интернет.

Топик на форуме: https://codeby.net/threads/infinite-bomber-sms-call-flud.68693/

После запуска программы необходимо ввести:
	1. Номер телефона в международном формате без + в начале
	2. Режим лога: 0 - Лог выключен, 1 - Показывать только сообщения об удавшихся запросах, 2 - Показывать сообщения только о неудавшихся запросах, 3 - Показывать все сообщения
	3. Сколько времени спамить (в секундах). 0 - спамить бесконечно

Есть возможность запуска через консоль, с указанием всех параметров в аргументах
infinite-bomber [Номер телефона] [Режим флуда] [Режим логирования] [Время спама (в секундах)]
Пример: ./infinite-bomber 79214321234 3 3 600

Если использовать режим без лога, то программа будет "жрать" меньше опреративной памяти

В файле services.yaml можно добавлять сервисы, которые будут использоваться бомбером для флуда.
Список переменных, которые можно использовать обозначая позицию для вписывания номера жертвы:
	<num> -> 79112345678
	<num2> -> 9112345678
	<num3> -> 7 (911) 234-56-78
	<num4> -> 7 (911) 234 56 78
	<num5> -> 7 (911)234-56-78
	<num6> -> 7(911)234 56 78
	<num7> -> 7 911 234-56-78
	<num8> -> 7 911 234 56 78

	<num9> -> 7(911)234-56-78
	<num10> -> 7(911)2345678

	<num11> -> 7%20(911)%20234-56-78
	<num12> -> 7%20(911)%20234%2056%2078
	<num13> -> 7%20(911)234-56-78
	<num14> -> 7(911)234%2056%2078
	<num15> -> 7%20911%20234-56-78
	<num16> -> 7%20911%20234%2056%2078

Режим тестирования включается установкой перменной среды INFIBOMBTEST=1


# how to install (EN)

$ apt install git

$ git clone https://github.com/SenTDI/Infinite-Bomber-android

$ cd Infinite-Bomber-android

$ cd (the directory with your processor (either C tor or not) For example, $ cd Infinite-Bomber-arm64-without-tor (-without-tor without tor) (arm64 bit capacity of your processor)

$ chmod 777 infinite-bomber

$ ./infinite-bomber


# Information (EN)
Internet access is required for the program to work.

Topic on the forum: https://codeby.net/threads/infinite-bomber-sms-call-flud.68693/

After starting the program, you must enter:
1. Phone number in international format without + at the beginning
2. Log mode: 0 - Log is off, 1 - Show only messages about failed requests, 2 - Show messages only about failed requests, 3 - Show all messages
3. How long to spam (in seconds). 0 - spam endlessly

It is possible to run through the console, indicating all parameters in the arguments
infinite-bomber [Phone number] [Flood mode] [Logging mode] [Spam time (in seconds)]
Example: ./infinite-bomber 79214321234 3 3 600


If you use the mode without a log, then the program will "eat" less operative memory

In the services.yaml file, you can add the services that the bomber will use for flooding.
List of variables that can be used to indicate the position to enter the victim number:
	<num> -> 79112345678
	<num2> -> 9112345678
	<num3> -> 7 (911) 234-56-78
	<num4> -> 7 (911) 234 56 78
	<num5> -> 7 (911)234-56-78
	<num6> -> 7(911)234 56 78
	<num7> -> 7 911 234-56-78
	<num8> -> 7 911 234 56 78

	<num9> -> 7(911)234-56-78
	<num10> -> 7(911)2345678

	<num11> -> 7%20(911)%20234-56-78
	<num12> -> 7%20(911)%20234%2056%2078
	<num13> -> 7%20(911)234-56-78
	<num14> -> 7(911)234%2056%2078
	<num15> -> 7%20911%20234-56-78
	<num16> -> 7%20911%20234%2056%2078

Testing mode is activated by setting the variable environment INFIBOMBTEST=1


