---
# Front matter
lang: ru-RU
title: "Лабораторная работа №8"
subtitle: "Дисциплина: Операционные системы"
author: "Кабанова Варвара Дмитриевна"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Выполнение лабораторной работы

Выполнение 1 задания:

Создала каталог с именем ~/work/os/lab06 с помощью команды mkdir (опция -p позволяет создать все каталоги, которые указаны внутри пути) (рис.1). 

![рис.1](image/1.png){ #fig:001 width=70% }

Командой «cd work/os/lab06» перешла в созданный каталог (рис.2).

![рис.2](image/2.png){ #fig:002 width=70% }

Вызвала vi и создала файл hello.sh с помощью команды «vi hello.sh» (рис.3).

![рис.3](image/6.png){ #fig:003 width=70% }

Нажимаем клавишу «i» и вводим текст, указанный в лабораторной работе (рис.4).

![рис.4](image/3.png){ #fig:004 width=70% }

Нажимаем клавишу «esc», чтобы перейти в командный режим после завершения ввода текста 

Нажимаем «:» для перехода в режим последней строки и внизу экрана видим, что появилось приглашение в виде двоеточия (рис.5).

![рис.5](image/4.png){ #fig:005 width=70% }

Нажала «w» (записать) и «q» (выйти), далее нажимаю клавишу «enter» для сохранения текста и завершения работы (рис.6).

![рис.6](image/5.png){ #fig:006 width=70% }

Чтобы сделать файл исполняемым, использую команду «chmod +x hello.sh (рис.7).

![рис.7](image/7.png){ #fig:007 width=70% }

Выполнение 2 задания:

Вызовем vi для редактирования файла с помощью  команды «vi ~/work/os/lab06/hello.sh» (рис.8).

![рис.8](image/8.png){ #fig:008 width=70% }

Далее с помощью стрелок установила курсор в конец слова HELL второй строки.Перешла в режим вставки, нажав на клавишу «i», и заменила HELL на HELLO, дописав O. Нажала «esc» для возврата в командный режим (рис.9).

![рис.09](image/9.png){ #fig:009 width=70% }

С помощью стрелок установила курсор на четвертую строку и стёрла слово LOCAL с помощью комбинации клавиш «d» (delete) и «w» (word) (рис.10).

![рис.10](image/10.png){ #fig:010 width=70% }

Перешла в режим вставки, нажав клавишу «i», и набрала следующий текст: local. Нажала «esc» для возврата в командный режим (рис.11).

![рис.11](image/11.png){ #fig:011 width=70% }

Установила курсор на последней строке файла, используя стрелки. Вставила после неё строку, содержащую следующий текст: echo $HELLO (рис.12).

![рис.12](image/12.png){ #fig:012 width=70% }

Далее нажала «esc», чтобы перейти в командный режим.

Удалила последнюю  строку,  используя  комбинацию  клавиш «d» и «d» (рис.13).

![рис.13](image/13.png){ #fig:013 width=70% }

Ввела команду отмены изменений «u» для отмены последней команды (рис.14).

![рис.14](image/14.png){ #fig:014 width=70% }

Ввела символ «:» для перехода в режим последней строки. Записала произведённые изменения, нажав «w» и «q» и вышла из vi (рис.15).

![рис.15](image/15.png){ #fig:015 width=70% }

# Контрольные вопросы:

1) Редактор vi имеет три режима работы:

- командный режим − предназначен для ввода команд редактирования и навигации по редактируемому файлу;

- режим  вставки  − предназначен  для  ввода  содержания редактируемого файла;

- режим последней (или командной) строки − используется для записи изменений в файл и выхода из редактора.

2) Чтобы выйти из редактора, не сохраняя произведённые изменения, нужно в режиме командной строки нажать клавиши «:» «q» «!»

3) Команды позиционирования:

- «0»(ноль) − переход в начало строки;

- «$» − переход в конец строки;

- «G» − переход в конец файла;

- n«G» − переход на строку с номером n.

4) При использовании прописных W и B под разделителями понимаются только  пробел,  табуляция  и  возврат  каретки.  При  использовании строчных w и b под разделителями понимаются также любые знаки пунктуации.

5) Чтобы из любого места редактируемого файла перейти в начало (конец) файла, нужно в режиме командной строки нажать клавиши «1» «G» («G»).

6) Команды редактирования:

1. Вставка текста

- «а» − вставить текст после курсора;

- «А» − вставить текст в конец строки;

- «i» − вставить текст перед курсором;

- n «i» − вставить текст n раз;

- «I» − вставить текст в начало строки.

2. Вставка строки

- «о» − вставить строку под курсором;

- «О» − вставить строку над курсором.

3. Удаление текста

- «x» − удалить один символ в буфер;

- «d» «w» − удалить одно слово в буфер;

- «d» «$» − удалить в буфер текст от курсора до конца строки;

- «d» «0» − удалить в буфер текст от начала строки до позиции курсора;

- «d» «d» − удалить в буфер одну строку;

- n «d» «d» − удалить в буфер n строк.

4. Отмена и повтор произведённых изменений

- «u» − отменить последнее изменение;

- «.» − повторить последнее изменение.

5. Копирование текста в буфер

- «Y» − скопировать строку в буфер;

- n «Y» − скопировать n строк в буфер;

- «y» «w» − скопировать слово в буфер.

6. Вставка текста из буфера

- «p» − вставить текст из буфера после курсора;

- «P» − вставить текст из буфера перед курсором.

7. Замена текста

- «c» «w» − заменить слово;

- n «c» «w» − заменить nслов;

- «c» «$» − заменить текст от курсора до конца строки;

- «r» − заменить слово;

- «R» − заменить текст.

8. Поиск текста

- «/» текст − произвести поиск вперёд по тексту указанной строки символов текст;

- «?» текст − произвести поиск назад по тексту указанной строки символов текст.

9. Копирование и перемещение текста

- «:» n,m «d» – удалить строки с n по m;

- «:» i,j «m» k – переместить строки с i по j, начиная со строки k;

- «:» i,j «t» k – копировать строки с i по j в строку k;

- «:» i,j «w» имя-файла – записать строки с i по j в файл с именем имя-файла.

7) Чтобы заполнить строку символами $, необходимо для начала перейти на эту строку, нажав клавиши n «G», где n – номер строки, далее нажать «0» для перехода в начало строки. Теперь необходимо нажать «c» «$», чтобы заменить текст от курсора до конца строки, и ввести символы $.

8) Чтобы отменить по одному предыдущему действию последовательно, необходимо нажать «u». Чтобы отменить все изменения, произведённые со времени последней записи, нужно нажать «:» «e» «!».

9) Команды редактирования в режиме командной строки

1. Копирование и перемещение текста

- «:»n,m «d» − удалить строки с n по m;

- «:»i,j «m» k − переместить строки с i по j, начиная со строки k;

- «:»i,j «t» k − копировать строки с i по j в строку k;

- «:»i,j «w» имя-файла − записать строки с i по j в файл с именем имя-файла.

2. Запись в файл и выход из редактора

- «:» «w» − записать изменённый текст в файл, не выходя из vi;

- «:» «w» имя-файла − записать изменённый текст в новый файл с именем имя-файла;

- «:» «w» «!» имя-файла − записать изменённый текст в файл с именем имя-файла;

- «:» «w» «q» − записать изменения в файл и выйти из vi;

- «:» «q» − выйти из редактора vi;

- «:» «q» «!» − выйти из редактора без записи;

- «:» «e» «!» − вернуться  в  командный  режим,  отменив  все изменения, произведённые со времени последней записи.

3. Опции

Опции редактора vi позволяют настроить рабочую среду. Для задания опций используется команда set (в режиме последней строки):

- «:»set all − вывести полный список опций;

- «:»set nu − вывести номера строк;

- «:»set list − вывести невидимые символы;

- «:»set  ic − не  учитывать  при  поиске,  является  ли  символ прописным или строчным.

Если вы хотите отказаться от использования опции, то в команде set перед именем опции надо поставить no.

10) Чтобы определить,  не  перемещая  курсора,  позицию,  в  которой заканчивается строка, нужно в командном режиме находясь на нужной строке нажать «$»и посмотреть на число после запятой в правом нижнем углу экрана 

11) Опции  редактора vi позволяют  настроить  рабочую  среду.  Для задания опций используется команда set (в режиме командной строки). Если вы хотите отказаться от использования опции, то в команде set перед именем опции надо поставить no. Чтобы просмотреть опции редактора vi, необходимо нажать «:» set all.  Нажав «:» help “название_опции”, можно узнать назначение конкретной опции.

12) В режиме командной строки внизу редактора присутствует «:», в режиме ввода – «--ВСТАВКА --», в командном режиме внизу ничего нет.

13) Граф взаимосвязи режимов работы редактора vi

# Выводы

В ходе лабораторной работы я познакомилась с операционной системой Linux. Получила практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.
