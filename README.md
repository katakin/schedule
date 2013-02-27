schedule
========

Для успешного запуска потребуется добавить файл config/application.yml:

sudo touch config/application.yml - для ubuntu

внутри файла добавляем этот текст:

GMAIL_USERNAME: Your_Username

GMAIL_PASSWORD: Your_Password

ADMIN_NAME: First User

ADMIN_EMAIL: user@example.com

ADMIN_PASSWORD: changeme

ROLES: [admin, user, VIP]

а потом добавляем базу данных через команду:

rake db:seed

Установка новой ветки
---------
Это пока чистый проект, каждый может создавать свою ветку и работать там:

git branch [name] - создание ветки

git checkout [name] - переход на ту ветку, по умолчанию ветка master.

git merge [name] - слияние двух веток. Осторожно!
