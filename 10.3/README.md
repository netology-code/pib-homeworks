# Домашнее задание к занятию «Защита сети»

### Цель задания

Информационная безопасность всё чаще становится поводом для беспокойства со стороны персонала АСУ ТП, поэтому необходимо разобраться, как правильно настроить безопасность сети.

В результате выполнения задания вы сможете:

1. Настроить списки доступа
1. Настроить фильтрацию по MAC-адресу

------

### Инструкция к заданию

1. Скачайте [Шаблон для домашнего задания](https://u.netology.ru/backend/uploads/lms/content_assets/file/2063/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%B4%D0%BB%D1%8F_%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B3%D0%BE_%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F__%D0%97%D0%B0%D1%89%D0%B8%D1%82%D0%B0_%D1%81%D0%B5%D1%82%D0%B8__-_%D0%A4%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D1%8F_%D0%98%D0%BC%D1%8F__%D0%A1%D0%94%D0%95%D0%9B%D0%90%D0%99%D0%A2%D0%95_%D0%9A%D0%9E%D0%9F%D0%98%D0%AE_.docx) на своё устройство.
2. Откройте скачанный файл на личном диске в Google.
3. В названии файла введите корректное название лекции и ваши фамилию и имя.
4. Зайдите в «Настройки доступа» и выберите доступ «Просматривать могут все в интернете, у кого есть ссылка». Инструкция «Как предоставить доступ к файлам и папкам на Google Диске» [по ссылке](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
5. Скопируйте текст задания в свой документ.
6. Выполните задание, запишите ответы и приложите необходимые скриншоты в свой Google-документ.
7. Для проверки домашнего задания отправьте ссылку на ваш Google-документ в личном кабинете.
8. Любые вопросы по решению задач можно задать в [чате поддержки](https://netology.ru/profile?modal=support&type=new-ticket) или в разделе «Вопросы по заданию» при выполнении практических заданий.
9. Подробнее о работе с Google-документами и загрузке решения на проверку можно найти в [«Руководстве по работе с материалами для обучения»](https://l.netology.ru/instruktsiya-po-materialami-dlya-obucheniya)


------

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. [Шаблон для домашнего задания](https://u.netology.ru/backend/uploads/lms/content_assets/file/2063/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%B4%D0%BB%D1%8F_%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B3%D0%BE_%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F__%D0%97%D0%B0%D1%89%D0%B8%D1%82%D0%B0_%D1%81%D0%B5%D1%82%D0%B8__-_%D0%A4%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D1%8F_%D0%98%D0%BC%D1%8F__%D0%A1%D0%94%D0%95%D0%9B%D0%90%D0%99%D0%A2%D0%95_%D0%9A%D0%9E%D0%9F%D0%98%D0%AE_.docx)
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
  
  
Вы можете воспользоваться инструкцией по установке [Cisco Packet Tracer (CPT)](https://u.netology.ru/backend/uploads/lms/content_assets/file/10653/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D1%8F_%D0%BF%D0%BE_%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B5_Cisco_Packet_Tracer.docx)

Работать в Cisco Packet Tracer можно:
- при отключении интернета на вашем устройстве, иначе будет требоваться авторизация;
- при заблокированном входящем и исходящем трафике для программы СРТ в брандмауэре. Сделать это можно, воспользовавшись [инструкцией](https://clck.ru/sXWvW);
- авторизоваться для работы, воспользовавшись инструкцией [по ссылке](https://disk.yandex.ru/i/abx_GySbEOhYAg).

Если у вас возникли сложности с установкой ПО с официального сайта, вы можете воспользоваться ссылками для скачивания программы. Выберите тот файл, который подходит для вашей операционной системы.

CPT для windows https://disk.yandex.ru/d/KqvfKAF_zKDIrg

CPT для macOS https://disk.yandex.ru/d/hyAkjwAn7SUiag

CPT для Linux https://disk.yandex.ru/d/iHX2MVbSy4NwLw
  
Если у вас возникнут дополнительные вопросы - напишите в чат группы или обратиться к координатору в системе обращений студентов на сайте по [ссылке](netology.ru/profile?modal=support&type=new-ticket)

Вы также можете написать о своей проблеме в разделе «Вопросы по заданию», доступном  в каждом практическом задании
  
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
