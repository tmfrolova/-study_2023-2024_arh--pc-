---
## Front matter
title: "Лабораторная работы №3"
subtitle: "Язык разметки Markdown"
author: "Фролова Татьяна Михайловна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Научится  процедуре оформления отчетов с помощью языка разметки Markdown,так же  научится создавать структурированные и читабельные документы.

# Задание

    1) Провести компиляцию шаблона с использованием Makefile;
    2) Удалить полученные файлы;
    3) Изучить файл report.md;
    4) Заполнить отчет и скомпилировать егос использованием Makefile;
    5) Загрузить файлы на Githud.

# Выполнение лабораторной работы
1.Открываем терминал и входим в определённые каталог ![Рис.1.1 Входим в каталог, необходимый для работы](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:001 width=70%}
Прописываем команду git pull. ![Рис.1.2 Команда git pull.](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:002 width=70%}
Пропишем команду make. ![Рис.1.3 Команда make.](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){fig:003 width=70%}
Пропишем команду ls ,чтобы проверить наличие файлов.![Рис.1.4 Файлы с папке.](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:004 width=70%}
Проверим корректность файлов.![Рис.1.5 Проверка корректности.](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:005 width=70%}
Пропишем команду make clean.![Рис.1.6  Команда make clean.](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:006 width=70%}
Проверим выволнение команды.![Рис.1.6  Команда make clean.](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:007 width=70%}
Откроем файл report.md c помощью gedit.![Рис.1.8 Команда gedit report.md . ](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:008 width=70%}
Изучаем открытый файл.![Рис.1.9 Файл report.md .](afs/.dk.sci.pfu.edu.ru/home/t/m/tmfrolova/Снимки экрана/){#fig:009	 width=70%}

# Выводы

Освоили Markdown – язык разметки, который помогает создавать отчеты просто и эффективно.



