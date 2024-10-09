---
## Front matter
title: "Отчёт по Лабораторной работе №2"
subtitle: "Система контроля версий Git"
author: "Фролова Татьяна михайловна"

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

Изучение и применение средств контроля версий с использованием Git, а так
же получить различные навыки по работе с системой.

# Задание

Настроить конфигурацию для работы с Git;
2)Освоить работу с созданием ключей;
3)Научится созданию рабочегого простанства и шаблона;
4)Ознакомиться с работой с репозиториями;
5)Научится настраивать каталог.


# Выполнение лабораторной работы

1.Открываем терминал и начинаем настройку Git ,с помощью следующих команд. Рис. 1.1 Выполняем настройку конфигурации.
Рис.1.2 Настраиваем utr-8.
Рис.1.3 Задаём имя начальной ветке.
Рис.1.4 Задаём параметр autocrlf.
Рис.1.5 Задаём параметр safecrlf.
2.Регистрируемся на предложенном для работы сайте .Рис. 2.1 Профиль на Gidhub.
3.Создаём ключ через терминал.Рис.3.1 Создание ключа.
Заходим на сайт,после в “настройки” и вставляем ключ.Рис.3.3 Ключ на сайте.
4.Создаём рабочее пространство и шаблон.Рис.4.1 Создание каталога и проверка
наличия.
5.Создание репозитории. Проходим по ссылке и создаём репозиторий.Рис.5.1 Создание репозитория.
6.Процесс клонирование .Рис.6.1 Клонирование репозитории.
7.Делаем настройки в каталоге курса.
Удаляем определенный файл и проверяем его отсутсвие. Рис.7.1 Удаление определенного файла.
Рис.7.2 Проверка удаления.
Рис.7.2 Создание необходимого каталога.
Рис.7.4 Команда git commit -am 'feat(main): make course structure'.
Рис.7.5 Команда gid push.
# Выводы
Освоить концепцию управления версиями и получили практические навыки работы с
системой Git.

