---
## Front matter
title: "Лабораторная работа №4"
subtitle: "Создание и процесс
обработки программ на языке ассемблера NASM"
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

Научиться компилировать и собирать программы на ассемблере NASM.

# Задание

    1) Создать программу "Hello world!" на ассемблере NASM;
    2) Скомпилировать и собрать программу с помощью транслятора NASM и компоновщика LD;
    3) Запустить файл программы. 

# Выполнение лабораторной работы
1.Открываем терминал и вводим следующую команду для создания каталога. ![создание каталога](создание каталога.png){#fig:001 width=70%}
Входим в созданный каталог ![вход в каталог](вход в каталог.png){#fig:001 width=70%}
Создаём нужный для работы файл ![создание файла](создание файла.png){#fig:001 width=70%}
Проверим его наличие. ![проверка наличия файла](проверка наличия файла.png){#fig:001 width=70%}
Откроем файл с помощью текстого редактора. ![открытие файла](открытие файла..png){#fig:001 width=70%}
Введём туда следующий текст. ![текст в файле](содержимое файлов.png){#fig:001 width=70%}
Даллее вводи команды и проверяем их исполение. ![Команды 1](команда1.png){#fig:001 width=70%}
![Проверка](проверка 1.png){#fig:001 width=70%}
![Команда 2](команда 2.png){#fig:001 width=70%}
![Проверка](проверка 2.png){#fig:001 width=70%}
![Команда 3](команда 3.png){#fig:001 width=70%}
![Проверка](проверка 3.png){#fig:001 width=70%}
![Команда 4](команда 4){#fig:001 width=70%}
Запустим созданный во время работы файл. ![Запуск файла](запуск.png){#fig:001 width=70%}
# Выводы

В ходе работы была освоена процедура компиляции и сборки программ, написанных на ассемблере NASM.

