https://github.com/okovtun/PV_319_NP.git
https://www.youtube.com/playlist?list=PLeqyOOqxeiIMzAvRbQJ6Hx_X6bUcvVFBg

UTP:
https://tripplite.eaton.com/products/ethernet-cable-types

VMware:
https://drive.google.com/file/d/1Hhy7_mlidPRJaWSSs79o7taahNFecWOL/view?usp=drive_link

References:
https://www.iana.org/
https://ssl-team.com/blog/kak-opredelit-shirokoveschatelnyy-adres-seti-po-ip-i-maske/#Posagovyj_algoritm_rasceta_sirokovesatelnogo_adresa

Win32:
SpinControl:	https://learn.microsoft.com/en-us/windows/win32/uxguide/ctrl-spin-controls
				https://learn.microsoft.com/en-us/windows/win32/controls/udm-setrange?redirectedfrom=MSDN

TODO:
1. Запустить Сервер на интерфейсе 127.0.0.1;
2. Определить все интерфейсы на локальной машине и предоставить пользователю выбор,
   на каком именно интерфейсе он хочет запустить программу;

DONE:
В поле 'Info', IP-адрес и Маска так же должны выводиться в двоичной системе счисления;

DONE:
Получить маску при помощи 'WM_NOTIFY' вместо 'EN_CHANGE';

DONE:
1. Напомнить про автономные IP-адреса;	DONE
2. Написать IP-калькулятор, который по введенным IP-адресу и маске вычисляет адрес сети, 
	широковещательный адрес и количество узлов сети.
	Должна быть возможность вводить маску как в полном виде, так и в сокращенном виде.

DONE:
1. Сеть класса 'C' 192.168.100.0 при помощи масок разделить на 2, 4, 8, 16, 32 и 64 подсети;

TODO:
1. Выучить теорию;
2. Почитать RFC-791:	https://datatracker.ietf.org/doc/html/rfc791
3. Почитать RFC-826:	https://datatracker.ietf.org/doc/html/rfc826
4. Почитать RFC-792:	https://datatracker.ietf.org/doc/html/rfc792
5. Используя анализатор протоколов Wireshark исследовать команду ping.
	(Какие сообщения отправляет, и какие сообщения получает, 
	 и что выводит на экран, если команда не получила никаких сообщений);
6. Используя анализатор протоколов Wireshark исследовать команду tracert;

TODO:
1. Изучить спецификации сетей
	FastEthernet:
		100Base-TX;
		100Base-T4;
		100Base-FX;
	GigabitEthernet:
		1000Base-T;
		1000Base-SX;
		1000Base-LX;
		1000Base-LH;
	2.5/5 GigabitEthernet:
		2.5GBase-T;
		  5GBase-T;
	10 Gigabit Ethernet:
2. Почитать про технологию Powerline!!!

TODO:
1. Закон Брустера;
2. Коннекторы для волоконно-оптических кабелей;
3. Изучить технологии семейства Ethernet:
	- Ethernet;
	- Fast Ethernet;
	- Gigabit Ethernet;
	- 2.5 Gigabit Ethernet;
	-   5 Gigabit Ethernet;
	-  10 Gigabit Ethernet;