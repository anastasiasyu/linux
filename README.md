# Linux Network

Настройка сетей в Linux на виртуальных машинах
Этот проект представляет собой пошаговое руководство по настройке сетей в Linux с использованием виртуальных машин. В рамках проекта я изучила и применила на практике ключевые аспекты работы с сетевыми протоколами, маршрутизацией, сетевыми экранами, DHCP, NAT и SSH-туннелями. Проект включает в себя как теоретическую часть, так и практические задания, которые помогли мне закрепить знания и навыки.

## Изучение основ сетей:

- Разобр модели OSI и стеком протоколов TCP/IP.

- Изучние принципов IP-адресации, маски подсети и маршрутизации.

- Работа с инструментом ipcalc:

- Определение адресов сетей, диапазонов хостов и преобразовование масок подсети.

- Различение частных и публичных IP-адреса.

## Настройка статической маршрутизации:
- Связывание двух виртуальных машин с помощью статических маршрутов.
- Настройка файлов конфигурации netplan для автоматического применения маршрутов.

## Измерение скорости сети:
- Использование утилиты iperf3 для проверки скорости соединения между машинами.

## Настройка сетевого экрана:
- Создание файрволов с помощью iptables для управления доступом к портам и блокировки ICMP-запросов.
- Применение разных стратегий настроек правил (запрет по умолчанию и разрешение по умолчанию).

## Статическая маршрутизация в сложной сети:
- Настройка сетей из пяти виртуальных машин (три рабочие станции и два роутера).
- Включение переадресации IP-пакетов и настройка маршрутов по умолчанию.
- Использование traceroute для анализа пути пакетов.

## Динамическая настройка IP с помощью DHCP:
- Настройка DHCP-сервера для автоматической выдачи IP-адресов.
- Проверка работы DHCP на виртуальных машинах.
- Настройка NAT (Network Address Translation):
- Реализация SNAT для маскировки локальных IP-адресов.
- Настройка DNAT для проброса портов и доступа к веб-серверу извне.

## SSH-туннели:
Использование Local и Remote TCP Forwarding для доступа к веб-серверу через SSH-туннели.

## Содержание:
Подробный отчёт с описанием выполненных задач, скриншотами и выводами команд.

Конфигурационные файлы: Примеры настроек netplan, iptables, dhcpd.conf и других.

Скрипты: Файлы для настройки файрволов и других задач.

## Навыки:
Настройка сетевых интерфейсов в Linux.

Работа с утилитами: ipcalc, iperf3, iptables, nmap, traceroute, tcpdump.

Настройка статической и динамической маршрутизации.

Работа с DHCP и NAT.

Создание и использование SSH-туннелей.

