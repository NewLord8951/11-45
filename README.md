# 11-45

1. Топология сети — это физическое расположение компьютеров сети друг относительно друга и способ соединения их линиями связи.

2. Структура сети типа «общая шина». Компьютеры (рабочие станции) подключены к одному кабелю с помощью специальных разъёмов. Чтобы сигнал не отражался от концов кабеля, их закрывают заглушками (терминаторами). Так существует всего одна линия связи, компьютеры передают данные по очереди. Сигнал, который идёт по шине, получают все компьютеры, но каждый из них обрабатывает только те данные, которые ему предназначены. 

Достоинства схемы «общая шина»:

самая простая и самая дешёвая схема; 
небольшой расход кабеля; 
легко подключать новые рабочие станции; 
при выходе из строя любого компьютера сеть продолжает работать. 
Недостатки схемы «общая шина»:

при разрыве кабеля или выходе из строя терминатора вся сеть не работает; 
низкий уровень безопасности (каждая рабочая станция имеет доступ ко всем данным, которые идут по сети); 
один канал связи на всех (при увеличении числа компьютеров падает скорость передачи; возможны конфликты, когда две рабочие станции хотят передать данные одновременно); 
сложно обнаруживать неисправности (неясно, где проблема); 
ограничение размера (не более 185 м, при большей длине нужны усилители сигнала). 
Структура сети типа «звезда». В сети, построенной согласно топологии «звезда», каждая рабочая станция соединена одним или двумя кабелями с центральным элементом. Центральное устройство управляет пересылкой информационных пакетов во всей сети. 

Достоинства схемы «звезда»:

при выходе из строя любой рабочей станции сеть остаётся работоспособной; 
высокий уровень безопасности (каждая рабочая станция получает только «свои» данные, а не все, что передаются по сети); 
простой поиск неисправностей и обрывов (сразу ясно, с каким компьютером нет связи). 
Недостатки схемы «звезда»:

большой расход кабеля, высокая стоимость; 
при выходе из строя коммутатора вся сеть не работает; 
количество рабочих станций ограничено количеством портов коммутатора. 
Структура сети типа «кольцо». Каждый компьютер соединён с двумя соседними, причём от одного он только получает данные, а другому только передаёт. 

3. Для школьной сети можно предложить использовать структуру «звезда». Она обеспечивает высокую скорость передачи данных и лёгкость в обслуживании. Если необходимо подключить много устройств, можно использовать «расширенную звезду» с несколькими коммутаторами. Это позволит легко управлять сетью и обеспечит надёжное соединение для всех учебных классов и лабораторий.
