# Лабораторная работа №2

### Выполнение:

1. Проверяю, что сервер с Ansible подключился к “клиенту”
![](screenshots/ansible_connected_to_client.png)
2. Создаю текстовый файл через shell
![](screenshots/test_file_creation.png)
3. Проверяю, что по нужному пути создался нужный файл с нужным именем и содержимым
![](screenshots/check_file_existance.png)
4. Удаляю файл через модуль file
![](screenshots/file_removal.png)
5. Инициализация Caddy
![](screenshots/check_caddy_installation.png)
6. Запускаю playbook: ansible-playbook caddy_deploy.yml и проверяю, успешно ли все шаги выполнились  
![](screenshots/check_caddy_execution.png)
7. Запускаю playbook, ввожу в браузере имя своего домена и убеждаюсь, что тестовая страничка Caddy автоматически поднялась на подписанном сертификате с https
![](screenshots/check_caddy_web_execution.png)
![](screenshots/caddy_web.png)

### Задания:

1) Создаю playbook (file_manager.yml) и запускаю его, чтобы:
   1. Создать файл
   2. Записать в него данные
   3. Поменять содержимое
   4. Удалить

   Playbook: ![](screenshots/file_manager_image.png)
   Выполнение: ![](screenshots/playbook_file_manager_execution.png)

2) Всю лабораторную работу выполнил на виртуальной машине и создал домен: lab2domen.duckdns.org
