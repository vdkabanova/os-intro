---
## Front matter
lang: ru-RU
title: Отчёт по лабораторной работе №10
author: Кабанова Варвара
institute: РУДН, Москва, Россия

date: 18 Мая 2022

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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы.

# Работа с консолью

Для начала я изучила команды архивации, используя команды «man zip», «man bzip2», «man tar» 

# Архиватор zip

Синтаксис команды zip для разархивации/распаковки файла: unzip [опции] [файл_архива.zip][файлы]-x[исключить]-d[папка] 

# Архиватор bzip2

Синтаксис команды bzip2 для разархивации/распаковки файла: bunzip2[опции] [архивы.bz2] 

# Скрипт №1

Написала скрипт, который при запуске будет делать резервную копию самого себя (то есть файла, в котором содержится его исходный код)  в другую  директорию back up в  вашем  домашнем  каталоге.

# Скрипт №2

Написала пример  командного  файла, обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее десять

# Скрипт №3

Написала  командный  файл − аналог  команды ls (без  использования самой этой команды и команды dir). Он должен выдавать информацию о нужном каталоге и выводить информацию о возможностях доступа к файлам этого каталога

# Скрипт №4

Написала командный  файл,  который  получает  в  качестве  аргумента командной строки формат файла (.txt, .doc, .jpg, .pdf и т.д.) и вычисляет количество таких файлов в указанной директории.

## {.standout}

В ходе выполнения данной лабораторной работы я изучила основы программирования в оболочке ОС UNIX/Linux и научилась писать небольшие командные файлы.

