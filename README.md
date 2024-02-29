# Домашнее задание к занятию "`Очереди RabbitMQ`" - `Пешкин Евгений`


### Задание 1. Установка RabbitMQ
Используя Vagrant или VirtualBox, создайте виртуальную машину и установите RabbitMQ. Добавьте management plug-in и зайдите в веб-интерфейс.

Итогом выполнения домашнего задания будет приложенный скриншот веб-интерфейса RabbitMQ.

#### Ответ
![Скриншот-1](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/1.png)


### Задание 2. Отправка и получение сообщений
Зайдите в веб-интерфейс, найдите очередь под названием hello и сделайте скриншот.

После чего запустите второй скрипт consumer.py и сделайте скриншот результата выполнения скрипта

#### Ответ 
![Скриншот-2](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/2.png)

![Скриншот-2.1](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/2.1.png)

### Задание 3. Подготовка HA кластера
В качестве решения домашнего задания приложите скриншоты из веб-интерфейса с информацией о доступных нодах в кластере и включённой политикой.


Также приложите вывод команды с двух нод:

$ rabbitmqctl cluster_status


Для закрепления материала снова запустите скрипт producer.py и приложите скриншот выполнения команды на каждой из нод:

$ rabbitmqadmin get queue='hello'


После чего попробуйте отключить одну из нод, желательно ту, к которой подключались из скрипта, затем поправьте параметры подключения в скрипте consumer.py на вторую ноду и запустите его.

Приложите скриншот результата работы второго скрипта.

#### Ответ 

![Скриншот-3](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/3.png)

![Скриншот-3.1](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/3.1.png)

![Скриншот-3.2](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/3.2.png)

![Скриншот-3.3](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/3.3.png)

![Скриншот-3.4](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/3.4.png)

![Скриншот-3.5](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/3.5.png)

![Скриншот-3.6](https://github.com/SoReX48/11-04.md/blob/main/Очереди_RabbitMQ/3.6.png)
