Домашнее задание
Первые шаги с Ansible

Описание/Пошаговая инструкция выполнения домашнего задания:

Для выполнения домашнего задания используйте методичку
https://drive.google.com/file/d/1CKknAPX-Ixnl4ClluCSbQQFne0PMsHBU/view?usp=share_link

Что нужно сделать?

Подготовить стенд на Vagrant как минимум с одним сервером. На этом сервере используя Ansible необходимо развернуть nginx со следующими условиями:

необходимо использовать модуль yum/apt;

конфигурационные файлы должны быть взяты из шаблона jinja2 с перемененными;

после установки nginx должен быть в режиме enabled в systemd;

должен быть использован notify для старта nginx после установки;

сайт должен слушать на нестандартном порту - 8080, для этого использовать переменные в Ansible.

В чат ДЗ отправьте ссылку на ваш git-репозиторий. Обычно мы проверяем ДЗ в течение 48 часов.

Если возникнут вопросы, обращайтесь к студентам, преподавателям и наставникам в канал группы в Slack.

Удачи при выполнении
