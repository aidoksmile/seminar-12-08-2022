# Инструкция по работе с Git

## Что такое Git
*Git* - одна из реализации распределенных систем контроля версий, позволяющая организовать версионность, как локально, так и на удаленном сервере. Самая популярная платформа, реализуящая *Git*, - [GitHub](https://github.com) 

## Подготовка репозитория
Для создания в папке репозитория необходимо открыть эту папку в терминале и написать команду *git init*, после чего в этой папке создасться скрытая папка *.git*, таким образом папка станет репозиторием

### Создание фиксации
Для создания фиксации используется команда *git commit*. Для этого в терминале папкой-репозиторием необходимо написать команду *git commit -m <сообщение к коммиту>. Сообщение к коммиту писать обязательно


### Просмотр состояния репозитория
Для просмотра состояния репозитория используется команда *git status*. В терминале с открытой папкой-репозитория необходимо написать команду *git status*. В результате можно увидеть следующие выводы:
1. On branch *** nothing to commit - это означает нет активных изменений
2. Untracked file - это означает, что имеются файлы, не отслеживаемые системой контроля версий
...

## Перемещение между коммитами

### Добавление файла к коммиту
Для того, чтобы добавить файл к "сохранению", необходимо использовать команду *git add*. В терминале с открытой папкой-репотизорием необходимо писать *git add <название файла>*. И этот файл добавится к "сохранению"

## Журнал зменений
Для просмотра историй изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log* и вы увидите список всех коммитов в этой ветке с описанием: имени, электронной почты, сообщением к коммиту и номер коммита.

## Перемещение между коммитами
Для перемещения между коммитами используется комманда *git checkout*. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout <номер коммита>. Номер коммита берется из журнала изменений ветки.

## Ветки в git
Ветвление это мощные инструмент и одна из главных фич git'а поскольку позволяет вам быстро создавать и переключатся между различным ветками вашего репозитория. Главная концепция ветвления состоит в том что вы можете откланяться от основной линии разработки и продолжать работу независимо от нее, не вмешиваясь в основную линию.
По умолчанию, имя основной ветки в *Git* — **master** 

## Конфликты

## Удаление веток