---
## Front matter
title: "Отчет по выполнению индивидульного проекта. 1 этап"
subtitle: "*Дисциплина: Операционные системы*"
author: "Кабанова Варвара Дмитриевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться размещать на Github pages заготовки для персонального сайта.

# Выполнение лабораторной работы

На туис в курсе "Операционные системы" в разделе индивидуальный проект перехожу в Техническую реализацию проекта. Здесь нам представлены различные ссылки (рис. 1). Я выбираю ссылку на репозитоий с общими файлами тем. Создаю новый репозиторий на основе шаблона (рис. 2). Называю свой репозиторий следюущим образом: personal-project- (рис. 4)

![рис.1](image/1.png){ #fig:001 width=70% }

![рис.2](image/2.png){ #fig:002 width=70% }

![рис.4](image/4.png){ #fig:004 width=70% }

Копирую ссылку на полученный репозиторий (рис. 3). Открываю терминал. Произвожу клонирвание с помощью команды git clone --recursive (рис. 5)

![рис.3](image/3.png){ #fig:003 width=70% }

![рис.5](image/5.png){ #fig:005 width=70% }

На туис в курсе "Операционные системы" в разделе индивидуальный проект перехожу в Инструкции. Перехожу по ссылке. Опускаюсь вниз страницы. Перехожу по ссылке в пункте 4.2 (Создание сайта на Hugo). Далее в пункте 1.2.3 (Ручная установка) перехожу по ссылке на архив с репозиториями (рис.6). Выбираю нужную версию (подчеркнута чертой) (рис.7). Произвожу установку. 

![рис.6](image/6.png){ #fig:006 width=70% }

![рис.7](image/7.png){ #fig:007 width=70% }

Архив сохраняется в загрузки. Извлекаю архив в текущую папку (рис. 8)

![рис.8](image/8.png){ #fig:008 width=70% }

Далее в домашней папке создаю пустую папку bin (рис.9), куда перемещаю файл hugo из нашего архива (рис.10).

![рис.9](image/9.png){ #fig:009 width=70% }

![рис.10](image/10.png){ #fig:010 width=70% }

Вызываю файл hugo через его адрес (рис.11-12)

![рис.11](image/11.png){ #fig:011 width=70% }

![рис.12](image/12.png){ #fig:012 width=70% }

Перехожу по полученной ссылке (рис. 13). 

![рис.13](image/13.png){ #fig:013 width=70% }

У нас открывается сайт, где на первой странице имеется зеленое поле с основной информацией о теме Academic (рис.14). 

![рис.14](image/14.png){ #fig:014 width=70% }

Это поле для ознакомления, нам оно не нужно, поэтому удаляю его. Посмотрим, в каком из файлов в репозитории, хранится текст, задающий эту страницу. 

![рис.15](image/15.png){ #fig:015 width=70% }

![рис.16](image/16.png){ #fig:016 width=70% }

Файл demo.md по адресу ~/work/study/2021-2022/Операционные системы/personal-project-/
content/home как раз является таковым, так как никакой иной информации он не содержит, мы можем его удалить (рис.17-19).

![рис.17](image/17.png){ #fig:017 width=70% }

![рис.18](image/18.png){ #fig:018 width=70% }

![рис.19](image/19.png){ #fig:019 width=70% }

Видим, как обновился сайт. Зеленое поле исчезло, остались нужные поля, первое из которых- биография (рис.20).

![рис.20](image/20.png){ #fig:020 width=70% }

Создаю новый репозиторий на github (рис. 21).

![рис.21](image/21.png){ #fig:021 width=70% }

Называю его особенным образом: vdkabanova.github.io (рис. 22)

![рис.22](image/22.png){ #fig:022 width=70% } 

Копирую ссылку на полученный репозиторий (рис. 23). Открываю терминал. Произвожу клонирвание с помощью команды git clone --recursive (рис. 24). Уведомление указывает нам, что репозиторий пустой. 

![рис.23](image/23.png){ #fig:023 width=70% }

![рис.24](image/24.png){ #fig:024 width=70% }

Перехожу в каталог нового путого репозитория. Переключаюсь на новую ветку main (рис. 25)

![рис.25](image/25.png){ #fig:025 width=70% }

Создаю пустой файл README.md (рис.26). 

![рис.26](image/26.png){ #fig:026 width=70% }

Выгружаю все на github (рис.27-29)

![рис.27](image/27.png){ #fig:027 width=70% }

![рис.28](image/28.png){ #fig:028 width=70% }

![рис.29](image/29.png){ #fig:029 width=70% }

Возвращаемся в каталог personal-progect- (рис. 30-31)

![рис.30](image/30.png){ #fig:030 width=70% }

![рис.31](image/31.png){ #fig:031 width=70% }

Связываем два репозитория с помощью команды git submodule add -b main. Добавляем подмодуль "public" (рис.32)

![рис.32](image/33.png){ #fig:032 width=70% }

Уведомление указывает нам на сбой в добавлении, с помощью команд ls, cat выясняем, где содержится другой каталог public (рис.33-34). 

![рис.33](image/34.png){ #fig:033 width=70% }

![рис.34](image/35.png){ #fig:034 width=70% }

Переходим в gitignore. Клмментируем с помощью # public. Сохраняем изменения (рис.35-37).
 
![рис.35](image/36.png){ #fig:035 width=70% }

![рис.36](image/37.png){ #fig:036 width=70% }

![рис.37](image/38.png){ #fig:037 width=70% }

Пробуем еще раз связать два репозитория с помощью команды git submodule add -b main. Добавление подмодуля "public" прошло успешно (рис.38-39)

![рис.38](image/37.png){ #fig:038 width=70% }

![рис.39](image/32.png){ #fig:039 width=70% }

Вызываю файл hugo через его адрес (рис.40). Видим, что каталог pubic заполнился файлами (рис. 41)

![рис.40](image/40.png){ #fig:040 width=70% }

![рис.41](image/41.png){ #fig:041 width=70% }

Перехожу в каталог public, проверяю, внешний вид ссылки (рис. 42) 

![рис.42](image/42.png){ #fig:042 width=70% }

В файле config.yaml по адресу ~/work/study/2021-2022/Операционные системы/personal-project-/config/_default изменяю ссылку (рис.43-44)

![рис.43](image/43.png){ #fig:043 width=70% }

![рис.44](image/44.png){ #fig:044 width=70% }

Вызываю файл hugo через его адрес (рис.45).

![рис.45](image/45.png){ #fig:045 width=70% }

 Отправляю все на github (рис. 46-48)

![рис.46](image/46.png){ #fig:046 width=70% }

![рис.47](image/47.png){ #fig:047 width=70% }

![рис.48](image/48.png){ #fig:048 width=70% }

Открываю github, вижу, что во второй репозиторий были отправлены файлы из первого (рис. 49), копирую имя репозитория (рис.50). Вставляю в поисковую строку (рис.51). Видим, что по новой ссылке у нас открывается сайт (рис. 52)

![рис.49](image/49.png){ #fig:049 width=70% }

![рис.50](image/50.png){ #fig:050 width=70% }

![рис.51](image/51.png){ #fig:051 width=70% }

![рис.52](image/52.png){ #fig:052 width=70% }

# Выводы

В ходе выполнения данной лабораторной работы я научилась размещать на Github pages заготовки для персонального сайта. Я установила необходимое программное обеспечение, скачала шаблон темы сайта, разместила его на хостинге git, установила параметр для URLs сайта, а также разместила заготовку сайта на Github pages.

::: {#refs}
:::
