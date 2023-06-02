Задание 1
Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

Ответ 1

![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/f472cf50-61c1-4d4d-9e03-cb198c9eecb2)
![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/bd127f66-b05f-441b-8703-cd733ece6660)
![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/810e5452-adc1-4fba-95cb-c52cfe71efa4)
![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/732fd46a-1d5e-4cdc-8bab-d8100fefe002)
![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/b11cc107-0b22-4792-98cf-a2bb26b82185)


Задание 2
Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

Ответ 2

![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/227765a7-926f-40b9-8c8a-c2739683efe2)
![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/732a385e-2c44-43b3-a13c-0043baf250dc)
![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/73573e45-f1ab-42d5-b599-aeabd91b2c1b)
![image](https://github.com/AlexanderSchelokov/Clustering-and-load-balancing-hw/assets/121572590/09bdb3e5-b873-4e44-8870-6bcfd0d63e81)

