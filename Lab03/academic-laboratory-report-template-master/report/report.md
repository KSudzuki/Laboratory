---
# Front matter
lang: ru-RU
title: "Лабораторная работа №3"
subtitle: "Введение в работу с Octave"
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

Научиться пользоваться основными инструментами платформы Octave.

# Задание

Выполнить задания, указанные в лабораторной работе.


# Выполнение лабораторной работы

1. Простейшие операции

![Простейшие операции](image/1.jpg){ #fig:001 width=70% }

2. Операции  векторами

![Операции с векторами](image/2.jpg){ #fig:002 width=70% }

3. Вычисление проектора 

![Вычисление проектора](image/3.jpg){ #fig:003 width=70% }

4. Матричные опперации

![Матричные операции 1](image/4.jpg){ #fig:004 width=70% }

![Матричные операции 2](image/5.jpg){ #fig:005 width=70% }

5. Построение простейших графиков

![График y=sin(x)](image/6.jpg){ #fig:006 width=70% }

![Улучшенный график y=sin(x)](image/7.jpg){ #fig:007 width=70% }

6. Два графика на одном чертеже

![Два графика на одном чертеже](image/8.jpg){ #fig:008 width=70% }

7. График y=x^2sinx

![График](image/9.jpg){ #fig:009 width=70% }

8. Сравнение циклов и операций с векторами

![Сравнение циклов и операций с векторами](image/10.jpg){ #fig:0010 width=70% }



# Выводы

Научились пользоваться основными инструментами Octave.

Здесь кратко описываются итоги проделанной работы.
