---
## Front matter
title: "Отчет по лабораторной работе №4"
subtitle: 
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

Овладеть практическими навыками легковесного языка разметки Markdown


# Выполнение лабораторной работы

1) Обновляем локальный репозиторий, скачав изменения из удаленного репозитория 

![Обновление репозитория.](image/1.png){ #fig:001 width=70% }

2) Проверяем команду make

![Команда make.](image/2.png){ #fig:002 width=70% }

3) Выполняем команду make clean

![Команда make clean.](image/3.png){ #fig:003 width=70% }

4) При помощи gedit открываем файл report.md

![Команда gedit.](image/4.png){ #fig:004 width=70% }

![Report.md с помощью gedit](image/5.png){ #fig:005 width=70% }

5) Заполняем отчет в файле report.md

![Отчет в report.md](image/6.png){ #fig:006 width=70% }

![Изображения в папке image](image/7.png){ #fig:007 width=70% }

6) Переносим файлы на github

![Перенос файлов на github](image/8.png){ #fig:008 width=70% }

# Выполнение самостоятельной работы
1) Я написала отчет по Л03 и создала отчеты в форматах pdf и docx

![Часть отчета по Л03](image/9.png){ #fig:009 width=70% }
2) Я загрузила файлы на github
# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
