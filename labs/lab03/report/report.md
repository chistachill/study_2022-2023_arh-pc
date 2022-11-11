---
## Front matter
title: "Отчет по лабораторной работе №3"
author: "Попова Елизавета Сергеевна"

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

Познакомиться с github и командой git. 


# Задание

Настроить GitHub, создать репозиторий, а также каталог курса. 


# Выполнение лабораторной работы

1) Создаем профиль на github

![Создание профиля на github](image/1.png){ #fig:001 width=70% }

2) Настроим git 

![Настраиваем конфиг при помощи некоторых команд](image/2.png){ #fig:002 width=70% }

3) Создадим SSH ключ и внесем его в github 

![Создание и вывод ключа](image/3.png){ #fig:003 width=70% }

![SSH ключ на github](image/4.png){ #fig:004 width=70% }

4) Создадим репозиторий 

![Репозиторий](image/5.png){ #fig:005 width=70% }

5) Найдем нужный репозиторий на github и скопируем его в свой профиль, затем скопируем SSH ключ 

![SSH ключ репозитория](image/6.png){ #fig:006 width=7 }

6) Клонируем созданный репозиторий и настроим каталог курса

![Клонирование](image/7.png){ #fig:007 width=7 }

![Настройка каталога](image/8.png){ #fig:008 width=7 }

![Настройка каталога](image/9.png){ #fig:009 width=7 }

![Проверка иерархии на github](image/10.png){ #fig:010 width=7 }

# Выполнение самостоятельной работы

1) Перенос отчет лабораторной работы в соответствующую папку

![Перенос папку в соответствующий каталог](image/11.png){ #fig:011 width=7 }

2) Перенос файла на github

![Перенос файлов на github](image/12.png){ #fig:012 width=7 }

3) Проверка выполнения

![Всё перенеслось верно](image/13.png){ #fig:013 width=7 }

# Выводы

В данной лабораторной работе мы познакомились с github и каталогами,
провели их настройку. Добавили прошлые работы в каталоге с помощью
терминала.

# Список литературы{.unnumbered}

::: {#refs}
:::
