---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №4
author: |
	Кабанова Варвара Дмитриевна
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 2022, 29 April 

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

# Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки

# Различные опции команды ls

- Чтобы отобразить имена скрытых файлов,использую команду ls с опцией a

- Использование опции F добавит символ «/» в конце каждого каталога

- Чтобы вывести на экран подробную информацию о файлах и каталогах,использую опцию l

- Чтобы вывести скрытые файлы, полную информацию о файлах и тип файлов, использую опцию alF

- Чтобы просмотреть содержимое не только указанного каталога,но и подкаталогов,входящих в него, использую опцию R

- Чтобы отсортировать по времени последнего изменения выводимый список содержимого каталогас развёрнутым описанием файлов, использую опцию lt 

# Создание новых каталогов

- В домашнем каталоге создаю новый каталог с именем newdir. В каталоге ~/newdir создаю новый каталог с именем morefun

- В домашнем каталоге создаю одной командой три новых каталога с именами letters,memos,misk

# Команда "удалить"

- Пробую удалить ранее созданный каталог ~/newdir командой rm

- Вижу, что удаление каталога невозможно, тк в нем имеется другой каталог

- Удаляю каталог с помощью команды rm-r

# Команда man

Использую команду man для просмотра описания следующих команд:

- cd 

- pwd

- mkdir 

- rmdir 

- rm

# Команда hisrory 

Выполняю модификацию и исполнение нескольких команд из буфера команд

## {.standout}

В ходе выполнения данной лабораторной работы я приобрела практические навыки взаимодействия пользователя с системой посредством командной строки
