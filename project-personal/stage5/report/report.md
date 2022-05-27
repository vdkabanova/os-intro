---
## Front matter
title: "Отчет по выполнению индивидульного проекта. 5 этап"
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

Научиться делать записи для персональных проектов

# Выполнение лабораторной работы

В папке ~/work/study/2021-2022/Операционные системы/personal-project-/
content/home вижу наличие многих файлов, один из которых- текстовый документ project.md. Поработаем с ним (рис. 1)

![рис.1](image/1.png){ #fig:001 width=70% }

Вносим изменения в наш файл, меняем названия блоков и тегов (рис. 2)

![рис.2](image/2.png){ #fig:002 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo (рис.3)

![рис.3](image/3.png){ #fig:003 width=70% }

Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис.4)

![рис.4](image/4.png){ #fig:004 width=70% }

В папке ~/work/study/2021-2022/Операционные системы/personal-project-/
content/project/example вижу наличие 2 файлов, один из которых- текстовый документ index.md. Поработаем с ним (рис. 5)

![рис.5](image/5.png){ #fig:005 width=70% }

Вношу изменения в файл, добавляя информацию по заданной теме (рис. 6)

![рис.6](image/6.png){ #fig:006 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo

Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис.7-9)

![рис.7](image/7.png){ #fig:007 width=70% }

![рис.8](image/8.png){ #fig:008 width=70% }

![рис.9](image/9.png){ #fig:009 width=70% }

При нажатии на клавишу 'more inf', мы оказываемся на странице википедии по заданной теме (рис.10)

![рис.10](image/10.png){ #fig:010 width=70% }

Проделываю аналогичные действия для второй вкладки (рис.11-16)

![рис.11](image/11.png){ #fig:011 width=70% }

![рис.12](image/12.png){ #fig:012 width=70% }

![рис.13](image/13.png){ #fig:013 width=70% }

![рис.14](image/14.png){ #fig:014 width=70% }

![рис.15](image/15.png){ #fig:015 width=70% }

![рис.16](image/16.png){ #fig:016 width=70% }

И такие же действия для третьей вкладки (рис.17-21)

![рис.17](image/17.png){ #fig:017 width=70% }

![рис.18](image/18.png){ #fig:018 width=70% }

![рис.19](image/19.png){ #fig:019 width=70% }

![рис.20](image/20.png){ #fig:020 width=70% }

![рис.21](image/21.png){ #fig:021 width=70% }

В терминале с помощью команды hugo создаю новый текстовый документ post7.md в папке post. Открываю файл и вношу изменения (рис. 22). 

![рис.22](image/22.png){ #fig:022 width=70% }

Помещаю документ и картинку к нему в отдельную папку post7, переименовываю текстовый документ в index.md, а картинку в featured.jpg 

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo. Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис.23-25)

![рис.23](image/41.png){ #fig:023 width=70% }

![рис.24](image/39.png){ #fig:024 width=70% }

![рис.25](image/40.png){ #fig:025 width=70% }

В терминале с помощью команды hugo создаю новый текстовый документ post8.md в папке post. Открываю файл и вношу изменения (рис.26-27). 

![рис.26](image/23.png){ #fig:026 width=70% }

![рис.27](image/24.png){ #fig:027 width=70% }

Помещаю документ и картинку к нему в отдельную папку post8, переименовываю текстовый документ в index.md, а картинку в featured.jpg 

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo. Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис.28-33)

![рис.28](image/33.png){ #fig:028 width=70% }

![рис.29](image/34.png){ #fig:029 width=70% }

![рис.30](image/35.png){ #fig:030 width=70% }

![рис.31](image/36.png){ #fig:031 width=70% }

![рис.32](image/37.png){ #fig:032 width=70% }

![рис.33](image/38.png){ #fig:033 width=70% }

В папке ~/work/study/2021-2022/Операционные системы/personal-project-/
content/slides/example вижу наличие текстового документа index.md. Поработаем с ним (рис. 34)

![рис.34](image/25.png){ #fig:034 width=70% }

Вношу изменения в файл, добавляя информацию по заданной теме (рис. 35)

![рис.35](image/26.png){ #fig:035 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo

Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось. При нажатии на окно 'slides' открывается презентация (рис.36-40)

![рис.36](image/27.png){ #fig:036 width=70% }

![рис.37](image/28.png){ #fig:037 width=70% }

![рис.38](image/29.png){ #fig:038 width=70% }

![рис.39](image/30.png){ #fig:039 width=70% }

![рис.40](image/31.png){ #fig:040 width=70% }

# Выводы

В ходе выполнения данной лабораторной работы я научилась делать записи для персональных проектов, написала пост о прошедшей неделе и пост на заданную тему

::: {#refs}
:::
