---
## Front matter
title: "Отчёт по лабораторной работе №8"
subtitle: "Модель конкуренции двух фирм"
author: "Козлов Всеволод Павлович НФИбд-02-22"

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
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: Arial
romanfont: Arial
sansfont: Arial
monofont: Arial
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

Исследовать математическую модель конкуренции двух фирм.

# Задание

1. Построить графики изменения объемов оборотных средств каждой фирмы в двух различных случаях:
- Случай 1: Конкуренция только на основе экономических факторов (себестоимость, производственный цикл).
- Случай 2: Учет социально-психологических факторов, влияющих на предпочтения потребителей.
2. Проанализировать полученные результаты и динамику изменения оборотных средств.

# Выполнение лабораторной работы

Формулировка задания (часть1) (рис. [-@fig:005])

![Формулировка задания](image/5.png){ #fig:005 width=70% }

Формулировка задания (часть2) (рис. [-@fig:006])

![Формулировка задания](image/6.png){ #fig:006 width=70% }

Формулировка задания (часть3) (рис. [-@fig:007])

![Формулировка задания](image/7.png){ #fig:007 width=70% }

Параметры модели, расчет коэффициентов (рис. [-@fig:001])

![Параметры модели, расчет коэффициентов](image/1.png){ #fig:001 width=70% }

Системы уравнений, решение систем (рис. [-@fig:002])

![Системы уравнений, решение систем](image/2.png){ #fig:002 width=70% }

Код для построения графиков (рис. [-@fig:003])

![Код для построения графиков](image/3.png){ #fig:003 width=70% }

Построение графиков (рис. [-@fig:004])

![Построение графиков](image/4.png){ #fig:004 width=70% }

# Выводы

Исследовал математическую модель конкуренции двух фирм.