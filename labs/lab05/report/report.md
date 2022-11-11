---
## Front matter
title: "Отчет по лабораторной работе №5"
subtitle: "Создание и процесс обработки программ на языке ассемблера NASM"
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

Освоить процедуры компиляции и сборки программ, написанных на
ассемблере NASM.

# Задание

Написать простейший код на ассемблере NASM.


# Выполнение лабораторной работы

1) Создаем каталог lab05 и переходим в него

![Создание каталога lab05](image/1.png){ #fig:001 width=70% }

![Переход к каталогу lab05](image/2.png){ #fig:002 width=70% }

2) Создаем файл hello.asm и открвыаем его при помощи команды gedit.

![Файл hello.asm](image/3.png){ #fig:003 width=70% }

3) Вводим необходимый текст

![Содержание файла hello.asm](image/4.png){ #fig:004 width=70% }

4) Компилируем код

![Компилирование кода](image/5.png){ #fig:005 width=70% }

5) Компиляция файла hello.asm в obj.o

![Компилирование файла](image/6.png){ #fig:006 width=70% }

6) Обработка компановщиком файлов hello.o и obj.o

![Компилирование файла](image/7.png){ #fig:007 width=70% }

7) Запускаем файл hello 

![Работа файла hello](image/8.png){ #fig:008 width=70% }

# Выполнения самостоятельной работы

1) При помощи команды cp делаем копию файла hello.asm с именем lab5.asm

![Файлы в каталоге lab05](image/9.png){ #fig:009 width=70% }

2) При помощи редактора gedit вносим изменения в файл lab5.asm

![Изменение кода в файле lab5.asm](image/10.png){ #fig:010 width=70% }

3) Оттранслируем полученный текст и выполним компоновку файла

![Изменение файла](image/11.png){ #fig:011 width=70% }

4) Запускаем файл lab5

![Запуск файла lab5](image/12.png){ #fig:012 width=70% }


5) Скопируем файлы в локальный репозиторий и загрузим их на Github

![Загрузка на GitHub](image/13.png){ #fig:013 width=70% }

# Выводы

Мы освоили процедуры компиляции и сборки программы, написанные на ассемблере NASM

