# Linux-Network

Проект представляет собой подробный отчет со скриншотами о проделанной работе в сети с 5 вируальными машинами(в т.ч. 2 роутера). \
Отчет лежит в папке src.

## Структура реализации:
- Статическая маршрутизация между двумя машинами
    - Добавление статического маршрута вручную
    - Добавление статического маршрута с сохранением
- Утилита iperf3
- Сетевой экран
    - Утилита iptables
    - Утилита nmap
- Статическая маршрутизация сети
    - Настройка адресов машин
    - Включение переадресации IP-адресов.
    - Установка маршрута по-умолчанию
    - Добавление статических маршрутов
    - Построение списка маршрутизаторов
    - Использование протокола ICMP при маршрутизации
- Динамическая настройка IP с помощью DHCP
- NAT
- Знакомство с SSH Tunnels

## Использованные технологии и утилиты: 

- Ubuntu 20.04 Server LTS
- TCP IP
- iperf3
- traceroute
- DHCP
- SSH Tunnels
- iptables
- firewall
- NAT (SNAT, DNAT)
- Apache2
- netplan
- tcpdump

Схема сети:
![network.png](src/Screenshots/network.png)