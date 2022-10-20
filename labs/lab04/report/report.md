---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "Простейший вариант"
author: "Дмитрий Сергеевич Кулябов"

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

Освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown. 

# Выполнение лабораторной работы

1. Открыл терминал. 

![Открываю](image/04_1.png){ #fig:001 width=70% }

2. Перешел в каталог курса. 

![Перехожу](image/04_2.png){ #fig:002 width=70% }

3. Обновил локальный репозиторий с помощью git pull.

![Обновляю](image/04_3.png){ #fig:003 width=70% }

4. Перешел в report.

![Перехожу](image/04_4.png){ #fig:004 width=70% }

5. Провел компиляцию шаблона с использованием Makefile. 

![Провожу](image/04_5.png){ #fig:005 width=70% }

6. Проверил наличие файлов.

![Проверяю](image/04_6.png){ #fig:006 width=70% }

7. Удалил полученные файлы. 

![Удаляю](image/04_7.png){ #fig:007 width=70% }

8. Проверил.

![Проверяю](image/04_8.png){ #fig:008 width=70% }

9. Открыл файл report.md c помощью gedit. (рис. [-@fig:009])

![Открываю](image/04_9.png){ #fig:009 width=70% }

# Выполнение самостоятельной работы

# Выводы

Освоил процедуры оформления отчетов с помощью легковесного языка разметки Markdown. 


