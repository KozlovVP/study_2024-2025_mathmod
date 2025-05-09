---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Задача о погоне"
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

Построить математическую модель для выбора правильной стратегии при решении примера задачи о погоне.

# Задание

1. Провести рассуждения и вывод дифференциальных уравнений,
если скорость катера больше скорости лодки в n раз (значение n задайте
самостоятельно)
2. Построить траекторию движения катера и лодки для двух случаев. (Задайте
самостоятельно начальные значения)
Определить по графику точку пересечения катера и лодки.

# Выполнение лабораторной работы

Рассчитал мой вариант лабораторной работы (рис. [-@fig:001])

![Вариант лабораторной работы](image/1.png){ #fig:001 width=70% }

Запрограммировал мат. модель, ч.1 (рис. [-@fig:002])

![Прграмма мат. модели, ч1](image/2.png){ #fig:002 width=70% }

Запрограммировал мат. модель, ч.2 (рис. [-@fig:003])

![Прграмма мат. модели, ч2](image/3.png){ #fig:003 width=70% }

Запрограммировал мат. модель, ч.3 (рис. [-@fig:004])

![Прграмма мат. модели, ч3](image/4.png){ #fig:004 width=70% }

Вывел траекторию движения катера для обоих случаев (рис. [-@fig:005])

![Траектория движения катера для обоих случаев](image/5.png){ #fig:005 width=70% }

Рассчитал точку пересечения лодки и катера для обоих случаев (рис. [-@fig:006])

![Точки пересечения лодки и катера для обоих случаев](image/6.png){ #fig:006 width=70% }

# Выводы

Построил математическую модель для выбора правильной стратегии при решении примера задачи о погоне.