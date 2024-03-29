# Домашнее задание к занятию «Коммерческий учёт (АИИС КУЭ)»

### Цель задания

Автоматизация в сфере энергетики - отдельное направление со своими правилами и регламентами. Несмотря на практическую сложность реализации, системы АИИС КУЭ всё чаще начинают внедряться в энергетическую отрасль. Обусловлено это, прежде всего, достаточно существенной экономии от её внедрения.

После выполнения данного задания вы сможете:

1. Понять принципы работы систем АИИС КУЭ и его места в современной автоматизации.
2. Получить практические навыки проектирования системы АИИС КУЭ.

------

### Инструкция к заданию

1. Скачайте [Шаблон для домашнего задания](https://u.netology.ru/backend/uploads/lms/content_assets/file/3820/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%B4%D0%BB%D1%8F_%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B3%D0%BE_%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F__%D0%9A%D0%BE%D0%BC%D0%BC%D0%B5%D1%80%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D1%83%D1%87%D1%91%D1%82__%D0%90%D0%98%D0%98%D0%A1%D0%9A%D0%A3%D0%AD___-_%D0%A4%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D1%8F_%D0%98%D0%BC%D1%8F__%D0%A1%D0%94%D0%95%D0%9B%D0%90%D0%99%D0%A2%D0%95_%D0%9A%D0%9E%D0%9F%D0%98%D0%AE_.docx) на своё устройство.
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

1. [Спецификация](https://u.netology.ru/backend/uploads/lms/content_assets/file/3821/%D0%A1%D0%BF%D0%B5%D1%86%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F.xlsx)
2. [Шаблон для домашнего задания](https://u.netology.ru/backend/uploads/lms/content_assets/file/3820/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%B4%D0%BB%D1%8F_%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B3%D0%BE_%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F__%D0%9A%D0%BE%D0%BC%D0%BC%D0%B5%D1%80%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D1%83%D1%87%D1%91%D1%82__%D0%90%D0%98%D0%98%D0%A1%D0%9A%D0%A3%D0%AD___-_%D0%A4%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D1%8F_%D0%98%D0%BC%D1%8F__%D0%A1%D0%94%D0%95%D0%9B%D0%90%D0%99%D0%A2%D0%95_%D0%9A%D0%9E%D0%9F%D0%98%D0%AE_.docx)

------

### Задание. Создание спецификации

Вы - ведущий инженер по автоматизации, и никто лучше вас не знает, как правильно спроектировать систему АИИС КУЭ. В связи с этим, руководство поставило задачу спроектировать такую систему на предприятии.
Имеются следующие входные данные:

1. Входная трансформаторная подстанция имеет вход (сторона высокого напряжения 10 кВ) и выход (сторона низкого напряжения 0,4 кВ). Мощность трансформатора - 1000 кВА.
2. Выход трансформатора развязан на 10 ячеек. Итоговая мощность всех ячеек - 506 кВА.

Распределение мощности ячеек:
- ячейка 1: 100 кВА
- ячейка 2: 70 кВА
- ячейка 3: 50 кВА
- ячейка 4: 10 кВА
- ячейка 5: 10 кВА
- ячейка 6: 20 кВА
- ячейка 7: 130 кВА
- ячейка 8: 90 кВА
- ячейка 9: 15 кВА
- ячейка 10: 11 кВА.

Спроектируйте систему АИИС КУЭ с учётом входных данных. Для этого произведите подбор следующего оборудования:
- трансформаторы тока
- электросчётчики с выходным интерфейсом
- устройства сбора и передачи данных (УСПД)
- дополнительное оборудование, необходимое для построения системы.

*Результатом выполнения данного задания будет [спецификация](https://u.netology.ru/backend/uploads/lms/content_assets/file/3821/%D0%A1%D0%BF%D0%B5%D1%86%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F.xlsx) с комплектом оборудования для работы АИИС КУЭ по заданным критериям.* 

------

### Правила приёма работы

1. Отправлена ссылка на документ (Google Doc) с выполненным заданием в личном кабинете.
2. Документ размещён на личном Google Диске.
3. К документу настроены права доступа «Просматривать могут все в Интернете, у кого есть ссылка».

------

### Критерии оценки

1. Зачёт - выполнены все задания, ответы даны в развёрнутой форме, в выполненных заданиях нет противоречий и нарушения логики.
2. На доработку - задание выполнено частично или не выполнено, в логике выполнения заданий есть противоречия, существенные недостатки.
