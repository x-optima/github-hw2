# Домашнее задание к занятию "`Название занятия`" - `Фамилия и имя студента`


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

### Задание 1


Установлены docker, серверы jenkins и nexus. Настроены как лекции.
Настроен файлы /etc/hosts /etc/docker/daemon.json

![Screenshot1](/screenshots/scr1_1.png)
![Screenshot2](/screenshots/scr1_2.png)
![Screenshot3](/screenshots/scr1_3.png)
![Screenshot4](/screenshots/scr1_4.png)
![Screenshot5](/screenshots/scr1_5.png)
![Screenshot6](/screenshots/scr1_6.png)
![Screenshot7](/screenshots/scr1_7.png)


---

### Задание 2

Выбран тип проекта pipeline. Создан новый проект. Вставлен код пайплайна. Собран заново с 5-го раза контейнер hello-world

![Screenshot1](/screenshots/scr2_1.png)
![Screenshot2](/screenshots/scr2_2.png)
![Screenshot3](/screenshots/scr2_3.png)
![Screenshot4](/screenshots/scr2_4.png)

### Задание 3

На github из проекта берем Dockerfile. Берем из него команду RUN CGO_ENABLED=0 GOOS=linux go build -a -installsuffix nocgo -o /app .
Далее, видоизменяем её и вставляем в pipeline на сервере jenkins.  

![Screenshot1](/screenshots/scr3_1.png)
![Screenshot2](/screenshots/scr3_2.png)
![Screenshot3](/screenshots/scr3_3.png)
![Screenshot4](/screenshots/scr3_4.png)
![Screenshot4](/screenshots/scr3_5.png)

### Задание 4

Переменная BUILD_NUMBER добавлена к имени собираеммого файла в таком виде _$BUILD_NUMBER

![Screenshot1](/screenshots/scr4_1.png)
![Screenshot2](/screenshots/scr4_2.png)
![Screenshot3](/screenshots/scr4_3.png)
