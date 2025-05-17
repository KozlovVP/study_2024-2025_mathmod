---
## Front matter
title: "Отчёт по лабораторной работе №7"
subtitle: "Эффективность рекламы"
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

Построить модель боевых действий и провести анализ.

# Задание

Между страной Х и страной У идет война. Численность состава войск
исчисляется от начала войны, и являются временными функциями x(t) и y(t). В
начальный момент времени страна Х имеет армию численностью 25 000 человек, а
в распоряжении страны У армия численностью в 45 000 человек. Для упрощения
модели считаем, что коэффициенты a, b, c, h постоянны. Также считаем P(t) и Q(t) непрерывные функции.
Необходимо построить графики изменения численности войск армии Х и армии У при регулярных/партизанских войсках.

# Выполнение лабораторной работы

Задал начальные условия из условия задачи (рис. [-@fig:001])

![Начальные условия](image/1.png){ #fig:001 width=70% }

Запрограммировал модель боевых действий между регулярными войсками (рис. [-@fig:002])

![Модель боевых действий между регулярными войсками](image/2.png){ #fig:002 width=70% }

Запрограммировал модель ведения боевых действий с участием регулярных войск и партизанских отрядов  (рис. [-@fig:003])

![Модель ведения боевых действий с участием регулярных войск и партизанских отрядов](image/3.png){ #fig:003 width=70% }

Написал код для построения графиков (рис. [-@fig:004])

![Код для построения графиков](image/4.png){ #fig:004 width=70% }

Программа вывела графики на экран (рис. [-@fig:005])

![Вывод графиков на экран](image/5.png){ #fig:005 width=70% }

В результате можно увидеть, что при таких параметрах модели армия $X$ побеждает армию $Y$

# Выводы

Построил модель боевых действий и провел анализ.