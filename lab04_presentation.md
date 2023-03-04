---
## Front matter
lang: ru-RU
title: Лабораторная работа № 4.
author: |
	Махорин Иван Сергеевич
institute: |
	RUDN, Москва, Россия
date: 2023, 4 март

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки

## Команда pwd

![Полное имя домашнего каталога](/home/liveuser/Downloads/msg444583747-364087 (copy).jpg){ #fig:001 width=70% }

Определение полного имени домашнего каталога с помощью команды pwd.

## Работа с каталогом /tmp

![Каталог /tmp](/home/liveuser/Downloads/msg444583747-364088.jpg){ #fig:002 width=70% }

## Команда ls

![ls](/home/liveuser/Downloads/msg444583747-364088.jpg){ #fig:003 width=70% }

Команда ls используется для просмотра содержимого каталога.

## Команда ls -a

![ls -a](/home/liveuser/Downloads/msg444583747-364089.jpg){ #fig:004 width=70% }

Команда ls -a используется для отображения имён скрытых файлов.

## Команда ls -l

![ls -l](/home/liveuser/Downloads/msg444583747-364090.jpg){ #fig:005 width=100% }

Команда ls -l используется для вывода на экран подробной информации о файлах и каталогах.

## Команда ls -F

![ls -F](/home/liveuser/Downloads/msg444583747-364124.jpg){ #fig:006 width=70% }

Команда ls -F используется для получения информации о типах файлов (каталог, исполняемый файл, ссылка).

## Команда ls -alF

![ls -alF](/home/liveuser/Downloads/msg444583747-364091.jpg){ #fig:007 width=100% }

## Поиск подкаталога с именем cron

![Отсутвие подкаталога с именем cron](/home/liveuser/Downloads/msg444583747-364092.jpg){ #fig:008 width=70% }

## Создание нового каталога newdir

![Создание нового каталога newdir](/home/liveuser/Downloads/msg444583747-364093.jpg){ #fig:009 width=100% }

## Создание подкаталога morefun

![Создание подкаталога morefun в каталоге newdir](/home/liveuser/Downloads/msg444583747-364094.jpg){ #fig:010 width=70% }

## Создание и удаление трёх каталогов сразу

![Создание и удаление каталогов одной командой](/home/liveuser/Downloads/msg444583747-364095.jpg){ #fig:012 width=100% }

## Удаление каталога newdir и подкаталога morefun из домашнего каталога

![Удаление каталога newdir и подкаталога morefun](/home/liveuser/Downloads/msg444583747-364096.jpg){ #fig:014 width=100% }

## Команда man ls

![Поиск нужной опции](/home/liveuser/Downloads/msg444583747-364098.jpg){ #fig:015 width=100% }

Опция -R - просмотр содержимого не только указанного каталога, но и подкаталогов.

## Команда man ls

![Поиск нужной опции](/home/liveuser/Downloads/msg444583747-364099.jpg){ #fig:016 width=100% }

-c -lt - набор опций команды, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога.

# Описание команд

## Команда cd 

Команда cd используется для перемещения по файловой системе операционной системы типа Linux.

![man cd](/home/liveuser/Downloads/msg444583747-364100.jpg){ #fig:017 width=100% }

## Команда pwd

Для определения абсолютного пути к текущему каталогу используется команда pwd (print working directory).

![man pwd](/home/liveuser/Downloads/msg444583747-364101.jpg){ #fig:018 width=100% }

## Команда mkdir

Команда mkdir используется для создания каталогов.

![man mkdir](/home/liveuser/Downloads/msg444583747-364102.jpg){ #fig:019 width=100% }

## Команда rmdir

Команда rmdir используется для удаления пустых каталогов. 

![man rmdir](/home/liveuser/Downloads/msg444583747-364103.jpg){ #fig:020 width=100% }

## Команда rm

Команда rm используется для удаления файлов и/или каталогов.

![man rm](/home/liveuser/Downloads/msg444583747-364104.jpg){ #fig:021 width=100% }

## История команд (history)

![Модификация и исполнение команд](/home/liveuser/Downloads/msg444583747-364097.jpg){ #fig:022 width=100% }

# Выводы

В ходе выполнения лабораторной работы были приобретены практические навыки взаимодействия пользователя с системой посредством командной строки.


## {.standout}

Спасибо за внимание!
