# mini-os
Операционная система, которая выводит "Hello world"
## Сборка
**Внимание! Для выполнения следующих действий вам нужна ОС Linux**
+ Введите в терминал команды:
```make all```,
```sudo make image```
+ Введите пароль учетной записи пользователя
+ У вас появится файл **hdd.img** - бинарный файл
+ Создайте загрузочный носитель или запустите ОС на виртуальной машине
## Назначение файлов
+ Makefile - скрипт сборки
+ loader.s - загрузчик
+ linker.ld - линкер (компоновщик)
+ kernel.s - ядро системы
