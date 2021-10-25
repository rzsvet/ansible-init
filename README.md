# Ansible role for initial virtual instances

## Переменные

### Описание

time_zone - временная зона
need_reboot - требуется перезагрузка, после применения

### Значения по-умолчанию

```YAML
---
time_zone: "Europe/Moscow"
need_reboot: true
```

## Установка

Добавить в файл requirements.yml
```
- src: https://github.com/rzsvet/ansible-init.git
```
Перед выполнением запустить
```
ansible-galaxy install -r requirements.yml
```

## Применение

Данная роль используется для первоначальной настройки экземпляров

## Примечание

Данная роль тестовая и врядли пригодится для использования в реальных проектах. Старайтесь не использовать сторонние роли, чтобы случайно не загрузить вредный код.
