# shdevops-4

Домашнее задание к занятию 4 «Оркестрация группой Docker контейнеров на примере Docker Compose»

Задача 1

https://hub.docker.com/repository/docker/artemduke/custom-nginx/general

Задача 2

![задача_2](https://github.com/ArtemDuke/shdevops-4/assets/161213872/654aff73-3e1d-420f-968d-5fad27b1d371)

контейнер остановился т.к. контейнер был "переведен" из режима демона в режим ввода/вывода и ему была послана комманда прерывания ctrl+c

Задача 3

![задание_3_1](https://github.com/ArtemDuke/shdevops-4/assets/161213872/e403365c-43f5-4784-8db7-7d1065c9caf7)
![задание_3_2](https://github.com/ArtemDuke/shdevops-4/assets/161213872/25e5869d-d117-4cdc-9ecb-9b5687f9330c)

ошибка из-за несоответствия портов указанных при старте контейнера и порта указанном в default.conf 

Задача 4

![задание_4](https://github.com/ArtemDuke/shdevops-4/assets/161213872/99098d52-5df2-4999-991a-44bf9956846b)

Задача 5
Docker-compose может использовать как compose.yaml так и docker-compose.yaml. Если существуют оба файла то docker-compose предпочтёт compose.yaml
![задание_5_1](https://github.com/ArtemDuke/shdevops-4/assets/161213872/50d0f2eb-5af2-4420-b48e-abf1c452b99c)
![задание_5_2](https://github.com/ArtemDuke/shdevops-4/assets/161213872/5b95a27e-b914-49a7-9534-cecded594d81)
![задание_5_3](https://github.com/ArtemDuke/shdevops-4/assets/161213872/c784b031-8ecb-468a-b020-f419fe0f9054)

docker-compose предупреждает что найден контейнер tasks-portainer-1 для которого отстутвует описание в compose.yaml. Предлагается очистить проект от этого контейнера выполнив команду с ключом --remove-orpahns

 ![задание_5_4](https://github.com/ArtemDuke/shdevops-4/assets/161213872/bf1adb4f-09f5-42d5-8c0f-3f650bb51cae)
