---
# Front matter
lang: ru-RU
title: "Отче по лабораторной работе №4"
subtitle: "Системы линейных уравнений"
author: "Ким Илья Владиславович"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучить применение Octave в системах линейных уравнений.

# Задание

Выполнить задания из лабораторной работы.


# Выполнение лабораторной работы

1. Метод Гаусса

![Метод Гаусса 1](image/1.jpg){ #fig:001 width=70% }

![Метод Гаусса 2](image/2.jpg){ #fig:002 width=70% }

2. Левое деление

![Левое деление 1](image/3.jpg){ #fig:003 width=70% }

![Левое деление 2](image/4.jpg){ #fig:004 width=70% }

3. LU - разложение

![LU - разложение](image/5.jpg){ #fig:005 width=70% }

4. LUP - разложение

![LUP - разложение](image/6.jpg){ #fig:006 width=70% }

# Выводы

Изучил применение Octave в системах линейных уравнений.
