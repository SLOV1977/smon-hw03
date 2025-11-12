# Домашнее задание к занятию "`Система мониторинга Zabbix. Часть 2`" - `Рахманов Александр`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

## Решение.

### Задание 1

### Создание шаблона, с элементами данных, мониторящих загрузку CPU и RAM хостов.

![Создание нового шаблона](https://github.com/SLOV1977/smon-hw03/tree/main/img/smon-hw-03-01.png)

![Создание нового шаблона](img/smon-hw-03-01.png)


![Item загрузки CPU в %](https://github.com/SLOV1977/smon-hw03/tree/main/img/smon-hw-03-02.png)

![Item загрузки CPU в %](img/smon-hw-03-02.png)


![Item загрузки RAM в %](https://github.com/SLOV1977/smon-hw03/tree/main/img/smon-hw-03-03.png)

![Item загрузки RAM в %](img/smon-hw-03-03.png)


![Созданные Items](https://github.com/SLOV1977/smon-hw03/tree/main/img/smon-hw-03-04.png)

![Созданные Items](img/smon-hw-03-04.png)

---

### Задание 2 и 3

### Добавление в Zabbix двух хостов с именами rakhmanovav-1 и rakhmanovav-2. Привязка к ним шаблона Task 1.

![Вкладка Configuration - Hosts](https://github.com/SLOV1977/smon-hw03/tree/main/img/smon-hw-03-05.png)

![Вкладка Configuration - Hosts](img/smon-hw-03-05.png)


![Вкладка Monitoring - Latest data](https://github.com/SLOV1977/smon-hw03/tree/main/img/smon-hw-03-06.png)

![Вкладка Monitoring - Latest data](img/smon-hw-03-06.png)

---

### Задание 4

### Создание дашборда Task 4.

![Дашборд Task 4](https://github.com/SLOV1977/smon-hw03/tree/main/img/smon-hw-03-07.png)

![Дашборд Task 4](img/smon-hw-03-07.png)

---