# The basics of GIT

# **Домашнее задание к занятию «Основы Git»»**

---

### Задание 1. Знакомимся с GitLab и Bitbucket

**GitLab**  

Создал аккаунт в GitLab.

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/1.png)

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/2.png)

### Задание 2. Теги

Представьте ситуацию, когда в коде была обнаружена ошибка - надо вернуться на предыдущую версию кода, исправить ее и выложить исправленный код в продакшн.   
Мы никуда код выкладывать не будем, но пометим некоторые коммиты тегами и создадим от них ветки.  
Создайте легковестный тег v0.0 на HEAD коммите и запуште его во все три добавленных на предыдущем этапе upstream.  
Аналогично создайте аннотированный тег v0.1.  
Перейдите на страницу просмотра тегов в гитхабе (и в других репозиториях) и посмотрите, чем отличаются созданные теги.  

GitHub теги https://github.com/Byzgaev-I/devops-netology/tags

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/3%20GitHub.png)

GitLab https://gitlab.com/Byzgaev-I/devops-netology-gitlab/-/tags

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/4GitLab.png)



![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/5.png)

### Задание 3. Ветки 

Давайте посмотрим, как будет выглядеть история коммитов при создании веток.  
Переключитесь обратно на ветку main, которая должна быть связана с веткой main репозитория на github.  
Посмотрите лог коммитов и найдите хеш коммита с названием Prepare to delete and move, который был создан в пределах предыдущего домашнего задания.  
Выполните git checkout по хешу найденного коммита.  
Создайте новую ветку fix базируясь на этом коммите git switch -c fix.  
Отправьте новую ветку в репозиторий на гитхабе git push -u origin fix.  
Посмотрите, как визуально выглядит ваша схема коммитов:  https://github.com/Byzgaev-I/devops-netology/network

Учусь работать под разными Git-клиентами, поэтому выслал и скрин с GitKraken. Вроде даже показалась удобной, но я пока в процессе обучения.

Network graph  https://github.com/Byzgaev-I/devops-netology/network

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/6%20GitHub.png)

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/7.png)

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/8.png)

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/9.png) 

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/10.png)

### Задание 4. Упрощаем себе жизнь

Попробуем поработь с Git при помощи визуального редактора.
В используемой IDE PyCharm откройте визуальный редактор работы с Git, находящийся в меню View -> Tool Windows -> Git.
Измените какой-нибудь файл, и он сразу появится на вкладке Local Changes, отсюда можно выполнить коммит, нажав на кнопку внизу этого диалога.
Элементы управления для работы с Git будут выглядеть примерно так:

Установил. 
Учусь. 

![image](https://github.com/Byzgaev-I/The-basics-of-GIT/blob/main/11%20PyCharm%20.png)









