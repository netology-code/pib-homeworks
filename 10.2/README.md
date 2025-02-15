# Домашнее задание к занятию «Защита хоста»

### Цель задания

В результате выполнения этого задания вы на практике познакомитесь с настройками безопасности ОС Windows.
Информационная безопасность всё чаще становится поводом для беспокойства со стороны персонала АСУ ТП, поэтому необходимо разобраться, с помощью как правильно настроить безопасную эксплуатацию хоста.

В результате выполнения задания вы сможете:

1. Настроить межсетевой экран
1. Настроить аудит изменения файлов

------

### Инструкция к заданию

1. Скачайте [Шаблона для домашнего задания](https://u.netology.ru/backend/uploads/lms/content_assets/file/5650/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%B4%D0%BB%D1%8F_%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B3%D0%BE_%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F__%D0%97%D0%B0%D1%89%D0%B8%D1%82%D0%B0_%D1%85%D0%BE%D1%81%D1%82%D0%B0__-_%D0%A4%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D1%8F_%D0%98%D0%BC%D1%8F__%D0%A1%D0%94%D0%95%D0%9B%D0%90%D0%99%D0%A2%D0%95_%D0%9A%D0%9E%D0%9F%D0%98%D0%AE_.docx) на своё устройство.
2. Откройте скачанный файл на личном диске в Google.
3. В названии файла введите корректное название лекции и ваши фамилию и имя.
4. Зайдите в «Настройки доступа» и выберите доступ «Просматривать могут все в интернете, у кого есть ссылка». Инструкция «Как предоставить доступ к файлам и папкам на Google Диске» [по ссылке](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
5. Скопируйте текст задания в свой документ.
6. Выполните задание, запишите ответы и приложите необходимые скриншоты в свой Google-документ.
7. Для проверки домашнего задания отправьте ссылку на ваш Google-документ в личном кабинете.
8. Любые вопросы по решению задач можно задать в чате учебной группы, в чате поддержки или в разделе «Вопросы по заданию» в личном кабинете.
9. Подробнее о работе с Google-документами и загрузке решения на проверку можно найти в [«Руководстве по работе с материалами для обучения»](https://l.netology.ru/instruktsiya-po-materialami-dlya-obucheniya)


------

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. [Шаблон для домашнего задания](https://u.netology.ru/backend/uploads/lms/content_assets/file/5650/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%B4%D0%BB%D1%8F_%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B3%D0%BE_%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F__%D0%97%D0%B0%D1%89%D0%B8%D1%82%D0%B0_%D1%85%D0%BE%D1%81%D1%82%D0%B0__-_%D0%A4%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D1%8F_%D0%98%D0%BC%D1%8F__%D0%A1%D0%94%D0%95%D0%9B%D0%90%D0%99%D0%A2%D0%95_%D0%9A%D0%9E%D0%9F%D0%98%D0%AE_.docx)
1. [Как настроить брандмауэр Windows и правила](https://sonikelf.ru/kak-nastroit-brandmauer-windows/)
1. [Открытие порта в брандмауэре Windows](https://cloudlite.ru/faq/nastroyka-brandmauera-windows-server/)
1. [How to Audit File Accesses, Read Events](https://www.lepide.com/how-to/track-who-read-files-on-your-windows-file-servers.html)
1. [Применение базовой политики аудита к файлу или папке](https://learn.microsoft.com/ru-ru/windows/security/threat-protection/auditing/apply-a-basic-audit-policy-on-a-file-or-folder)
1. [Аудит доступа к файлам и папкам Windows ](https://oblako.kz/help/windows/audit-dostpa-k-failam-windows-server)
1. [Аудит доступа к объектам](https://www.osp.ru/winitpro/2001/05/174875)

-----

### Задание 1 (Межсетевой экран)

1. Создайте правило, запрещающее выход в интернет программе **Internet Explorer**

*Приведите ответ в свободной форме и подтверждение факта блокировки в виде снимка экрана*

------

### Задание 2 (Аудит доступа)

1. Создайте на рабочем столе папку **SCADA**
2. Добавьте в созданную папку текстовый файл **config.cfg** с произвольным содержанием
3. Настройте аудит доступа для изменения содержимого данного файла

*! Используйте редакцию Windows, отличную от home. Например, professional или enterprise.*

*Приведите ответ в свободной форме и подтверждение аудита в виде снимка экрана*

------

### Правила приёма работы

1. Отправлена ссылка на документ (Google Doc) с выполненным заданием в личном кабинете.
2. Документ размещён на личном Google Диске.
3. К документу настроены права доступа «Просматривать могут все в Интернете, у кого есть ссылка».

------

### Критерии оценки

Зачёт:

- Предоставлены ответы и снимки экрана, точно отвечающие заданию.


На доработку:

- Задание выполнено частично или не выполнено.
