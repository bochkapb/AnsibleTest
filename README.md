# LevelUP: Ansible Homework

## Запуск первого ДЗ:
_в ДЗ было сказано собрать и запустить boxfuse на одной машине, но я сразу реализовал на двух._
```
ansible-playbook boxfuse.yml --ask-become-pass
```
## Запуск второго ДЗ:
_запуск Nginx и замена строки_
```
ansible-playbook nginx.yml --ask-become-pass
```
## Запуск третьего ДЗ:
_разворачивание проекта boxfuse по ролям_
```
ansible-playbook boxfuse-roles.yml --ask-become-pass
```
