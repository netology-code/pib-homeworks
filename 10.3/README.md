# Домашнее задание к занятию «Защита сети»

### Цель задания

Информационная безопасность всё чаще становится поводом для беспокойства со стороны персонала АСУ ТП, поэтому необходимо разобраться, как правильно настроить безопасность сети.

В результате выполнения задания вы сможете:

1. Настроить списки доступа
1. Настроить фильтрацию по MAC-адресу

------

### Инструкция к заданию

1. Сделайте копию [Шаблона для домашнего задания](https://docs.google.com/document/d/1WYqm6iwLYFV5vl7A4mG7zgpFGpNDOyLp5y4aD3iatvo/edit?usp=sharing) себе на Google Диск.
1. В названии файла введите корректное название лекции и вашу фамилию и имя.
1. Зайдите в «Настройки доступа» и выберите доступ «Просматривать могут все в Интернете, у кого есть ссылка». Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop)
1. Скопируйте текст задания в свой документ.
1. Скачайте и установите программу [Cisco Packet Tracer](https://www.netacad.com/ru/courses/packet-tracer).
1. Выполните домашнее задание, впишите ответы.
1. Для проверки домашнего задания преподавателем отправьте ссылку на ваш документ в личном кабинете.
1. Любые вопросы по решению задач задавайте в чате учебной группы.

------

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. [Шаблон для домашнего задания](https://docs.google.com/document/d/1WYqm6iwLYFV5vl7A4mG7zgpFGpNDOyLp5y4aD3iatvo/edit?usp=sharing)
2. [Cisco Packet Tracer](https://www.netacad.com/ru/courses/packet-tracer)
3. [Активация функции port-security.](https://artemsannikov.ru/cisco/packet-tracer/switchport-port-security-cpt/)
4. [Port secutity](http://ciscotips.ru/portsecurity)
5. [How to configure Switch Port Security in Packet Tracer](https://computernetworking747640215.wordpress.com/2019/11/12/switch-port-security/)
6. [Configure Standard Access Control List Step by Step Guide](https://www.computernetworkingnotes.com/ccna-study-guide/configure-standard-access-control-list-step-by-step-guide.html)
7. [Изучаем настройки ACL списки доступа в Cisco](https://litl-admin.ru/cisco/izuchaem-nastrojki-acl-spiski-dostupa-v-cisco.html)
8. [Packet Filtering using Access Control Lists (ACLS)](https://www.section.io/engineering-education/packet-filtering-using-acls/)
9. [ACL: списки контроля доступа в Cisco IOS](https://habr.com/ru/post/121806/)

<details>
  <summary> Что делать, если возникают вопросы или сложности по установке и работе с программным обеспечением? (доступно по клику)</summary>
  
  
1. Напишите в чат группы или обратиться к координатору в системе обращений студентов на сайте по [ссылке](netology.ru/profile?modal=support&type=new-ticket)

2. Можете написать о своей проблеме в разделе «Вопросы и ответы» к домашнему заданию
  
  ![image](https://github.com/netology-code/pwin-homeworks/blob/homeworks-pae-7/5.1/Q%26A.png)
    ---
  
</details>

-----

### Задание 1 (ACL 1)

1. В Cisco Packet Tracer соберите схему, рассмотренную на занятии ([схема](Network.JPG))
2. Настройте ACL так, чтобы PLC1 и PLC2 имели доступ к серверу, а PLC3 - нет.

*Приведите ответ в виде команд или снимков экрана*

------

### Задание 2 (ACL 2)

1. В Cisco Packet Tracer соберите схему, рассмотренную на занятии ([схема](Network.JPG))
2. Если нужно, удалите ACL из первого задания (no access-list <номер>)
3. Разрешите всем хостам (PLC1, PLC2, PLC3) доступ только с службе WWW сервера (Server)

*Приведите ответ в виде команд или снимков экрана*

------


### Правила приёма работы

1. Отправлена ссылка на документ (Google Doc) с выполненным заданием в личном кабинете.
2. Документ размещён на личном Google Диске.
3. К документу настроены права доступа «Просматривать могут все в Интернете, у кого есть ссылка».

------

### Критерии оценки

Зачёт:

- предоставлены команды или снимки экрана, на которых виден доступ к легитимным хостам или службам.
- предоставлены команды или снимки экрана, на которых видна блокировка нелегитимных хостов.

На доработку:

- задание выполнено частично или не выполнено.
