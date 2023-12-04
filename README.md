# OSPF
___
Цель:
* Создать домашнюю сетевую лабораторию.
* Научится настраивать протокол OSPF в Linux-based системах.

Выполнение:
Настройка VM и OSPF между машинами на базе Quagga

<a href="https://github.com/Arkady-Moiseev/ospf/blob/main/Vagrantfile">Vagrantfile</a>

<a href="https://github.com/Arkady-Moiseev/ospf/blob/main/ansible/ansible.cfg">ansible.cfg</a>

ansible-playbook -i ansible/hosts ansible/<a href="https://github.com/Arkady-Moiseev/ospf/blob/main/ansible/task1.yml">task1.yml</a>

![img_1](https://github.com/Arkady-Moiseev/ospf/blob/main/images/1.PNG)

![img_2](https://github.com/Arkady-Moiseev/ospf/blob/main/images/2.png)

![img_3](https://github.com/Arkady-Moiseev/ospf/blob/main/images/3.png)

![img_4](https://github.com/Arkady-Moiseev/ospf/blob/main/images/4.png)

![img_5](https://github.com/Arkady-Moiseev/ospf/blob/main/images/5.png)

2.2 Настройка ассиметричного роутинга

ansible-playbook -i ansible/hosts ansible/<a href="https://github.com/Arkady-Moiseev/ospf/blob/main/ansible/task3.yml">task2.yml</a>

![img_1](https://github.com/Arkady-Moiseev/ospf/blob/main/images/1.png)

![img_1](https://github.com/Arkady-Moiseev/ospf/blob/main/images/1.png)

2.3 Настройка симметичного роутинга

ansible-playbook -i ansible/hosts ansible/<a href="https://github.com/Arkady-Moiseev/ospf/blob/main/ansible/task3.yml">task3.yml</a>

![img_1](https://github.com/Arkady-Moiseev/ospf/blob/main/images/1.png)
