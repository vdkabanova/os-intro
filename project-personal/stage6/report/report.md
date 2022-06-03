---
## Front matter
title: "Отчет по выполнению индивидульного проекта. 6 этап"
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

Научиться размещать двуязычный сайт на гитхаб

# Выполнение лабораторной работы

В папке ~/work/study/2021-2022/Операционные системы/personal-project-/
config/_default вижу наличие многих файлов, один из которых- текстовый документ languages.yaml. Поработаем с ним (рис. 1)

![рис.1](image/1.png){ #fig:001 width=70% }

На сайте wowchemy.com узнаю, какой шифр имеют нужные мне языки (русский и английский) (рис. 2)

![рис.2](image/2.png){ #fig:002 width=70% }

Вношу изменения в наш файл(рис.3)

![рис.3](image/3.png){ #fig:003 width=70% }

Создаю копию файла menus.yaml. Переименовываю ее в menus.ru.yaml, а сам файл в menus.en.yaml (рис.4)

![рис.4](image/4.png){ #fig:004 width=70% }

Вношу изменения в файл menus.ru.yaml, перевожу заголовки на русский язык (рис. 5)

![рис.5](image/5.png){ #fig:005 width=70% }

В папке ~/work/study/2021-2022/Операционные системы/personal-project-/content/home создаю две подпапки en и ru, в каждую из которых к~/work/study/2021-2022/Операционные системы/personal-project- копирую все файлы, которые находились в самой папке home(рис. 6-7)

![рис.6](image/6.png){ #fig:006 width=70% }

![рис.7](image/7.png){ #fig:007 width=70% }

В папке ~/work/study/2021-2022/Операционные системы/personal-project-/content/en/authors/admin редактирую файл _index.md. Меняю русский текст на английский (рис.8-9)

![рис.8](image/8.png){ #fig:008 width=70% }

![рис.9](image/9.png){ #fig:009 width=70% }

В основной папке проекта ~/work/study/2021-2022/Операционные системы/personal-project- создаю папку i18n, куда помещаю два файла en.yaml и ru.yaml, скачанных с сайта wowchemy.com (рис.10)

![рис.10](image/10.png){ #fig:010 width=70% }

Во всех файлах папки ~/work/study/2021-2022/Операционные системы/personal-project-/content/en/home/ меняю русский текст на английский (рис.11-15)

![рис.11](image/11.png){ #fig:011 width=70% }

![рис.12](image/12.png){ #fig:012 width=70% }

![рис.13](image/13.png){ #fig:013 width=70% }

![рис.14](image/14.png){ #fig:014 width=70% }

![рис.15](image/15.png){ #fig:015 width=70% }

В папке vdkabanova/work/study/2021-2022/Операционные системы/personal-project-/content/en/post меняю текст всех постов, также перевожу их на английский (рис.16-23)

![рис.16](image/16.png){ #fig:016 width=70% }

![рис.17](image/17.png){ #fig:017 width=70% }

![рис.18](image/18.png){ #fig:018 width=70% }

![рис.19](image/19.png){ #fig:019 width=70% }

![рис.20](image/20.png){ #fig:020 width=70% }

![рис.21](image/21.png){ #fig:021 width=70% }

![рис.22](image/22.png){ #fig:022 width=70% }

![рис.23](image/23.png){ #fig:023 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo. Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого вызова команды ~/bin/hugo server). Отправляю все на гитхаб. Посмотрим, что изменилось (рис.24-27)

![рис.24](image/24.png){ #fig:024 width=70% }

![рис.25](image/25.png){ #fig:025 width=70% }

![рис.26](image/26.png){ #fig:026 width=70% }

![рис.27](image/27.png){ #fig:027 width=70% }

# Выводы

В ходе выполнения данной лабораторной работы я научилась размещать двуязычный сайт на гитхаб, сделала поддержку английского и русского языков, разместила элементы сайта на обоих языках, разместила контент на обоих языках, сделала пост по прошедшей неделе, а также пост на тему по выбору (на двух языках).

::: {#refs}
:::
