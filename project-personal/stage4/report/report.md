---
## Front matter
title: "Отчет по выполнению индивидульного проекта. 4 этап"
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

Научиться добавлять к сайту ссылки на научные и библиометрические ресурсы.

# Выполнение лабораторной работы

Открываю сайт, вижу, как сейчас выглядит поле с ссылками на различные ресурсы

![рис.1](image/1.png){ #fig:001 width=70% }

В папке ~/work/study/2021-2022/Операционные системы/personal-project-/
content/authors/admin вижу наличие 2 файлов, один из которых- текстовый документ _index.md. Поработаем с ним (рис. 2)

![рис.2](image/2.png){ #fig:002 width=70% }

Вносим изменения в наш файл, все поля заполняем по форме. которая представлена в комментариях (рис. 3)

![рис.3](image/3.png){ #fig:003 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo (рис.4)

![рис.4](image/4.png){ #fig:004 width=70% }

Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис.5)

![рис.5](image/5.png){ #fig:005 width=70% }

В терминале с помощью команды hugo создаю новый текстовый документ post5.md в папке post (рис.6)

![рис.6](image/6.png){ #fig:006 width=70% }

Открываю файл и вношу изменения (рис. 7). 

![рис.7](image/7.png){ #fig:007 width=70% }

Помещаю документ и картинку к нему в отдельную папку post5, переименовываю текстовый документ в index.md, а картинку в featured.jpg (рис.8)

![рис.8](image/8.png){ #fig:008 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo. Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис.9-10)

![рис.9](image/9.png){ #fig:009 width=70% }

![рис.10](image/10.png){ #fig:010 width=70% }

В терминале с помощью команды hugo создаю новый текстовый документ post6.md в папке post (рис.11)

![рис.11](image/11.png){ #fig:011 width=70% }

Открываю файл и вношу изменения (рис. 12). 

![рис.12](image/12.png){ #fig:012 width=70% }

Помещаю документ и картинку к нему в отдельную папку post6, переименовываю текстовый документ в index.md, а картинку в featured.jpg (рис.13)

![рис.13](image/13.png){ #fig:013 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo. Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис.14-17)

![рис.14](image/14.png){ #fig:014 width=70% }

![рис.15](image/15.png){ #fig:015 width=70% }

![рис.16](image/16.png){ #fig:016 width=70% }

![рис.17](image/17.png){ #fig:017 width=70% }

# Выводы

В ходе выполнения данной лабораторной работы я научилась добавлять к сайту ссылки на научные и библиометрические ресурсы, написала пост о прошедшей неделе и пост на заданную тему

::: {#refs}
:::
