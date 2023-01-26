# Инструкция по работе с Git

## Что такое Git?

**_Git_** - Это одна из реализаций распределенной системы контроля версий, поддерживает как локальные, так и удаленные репозитории.
Самая потулятная реализация Git - это [GitHub](https://github.com)

## Подготовка репозитория

Для создания репозитория использется команда "init". Для этого необходимо открыть в терминале папку с будующим репозиторием и там писать _git init_

## Создание 'сохранений'

Для создания сохранений надо нажать сочетание клавиш cmd + S.

## Добавление файла к комиту

Для добавления файла к коммиту используется команда _git add_. Для этого в терминале с папкой-репозиторием написать git add <название файла>.

## Перемещение между сохраниями

Перемещаться между сохранениями можно с помощью команды _git checkout <название коммита который нужен>_.

## Журнал изменений

Журнал изменений просматривает через команду _git log_

## Ветки в Git

Ветки в _Git_ создаются с помощью команды _git branch <название ветки>_. Переход на ветки с помощью команды _git checkout <название ветки>_.
Для этого в репозитории пишем

### Для просмотра списка веток исполльзуется git branch и вы увидите весь список всех сушествующих веток. Зеленым цветом и символом **звездочка**, будет обозначена текущая ветка.

## Слияние веток и решение конфликтов

Слияние веток происходит с помощью команды _git merge_. Быть надо на главной ветке, а к не дополнять другой коммит. Пишем _git merge <название ветки>_. Решение конфликтов происходит удалением всех лишних символов.

## Перемещение между ветками

Для перемещения между ветками используется команда git checkout. Для этого в терминале с папкой -репозиторием необходимо написать git checkout

## Создание комитов

Сохраняем изменения с помощью клавиш _CMD + S_. Создать коммит в репозитории можно с помощью команды _git add <название папки>_. Далее пишем команду _git commit - m "Название коммита"_.

### Выполнение комита

Для того, что-бы выполнить коммит используется команда _git commit_. Для этого в терминале с папкой репозиторием написать _git commit - m "yназвание коммита"_

## Для перемещениями между комитами

Для перемещениями между комитами используется команда _git checkout_. Для этого с папкой- репозиторием

## END
