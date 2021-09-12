---
# Front matter
lang: ru-RU
title: "Отчет по лабораторной работе №6"
subtitle: "Пределы, последовательности и ряды"
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

Научиться использовать Octave с пределами, последовательностями и рядами.

# Задание

1. Сделайте отчет по лабораторной работе в формате Markdown.

2. В качестве отчета просьба предоставить отчеты в 3 форматах: pdf,docx и md(в архиве, поскольку он должен содержать скриншоты, Markfile и т.д)

# Выполнение лабораторной работы

**Пределы, последовательности и ряды**

1. Анонимная функция

![Анонимная функция и вычисление предела 1](image/1.jpg){ #fig:001 width=70% }

![Анонимная функция и вычисление предела 2](image/2.jpg){ #fig:002 width=70% }

2. Частичные суммы

![Определение вектора n и вычисление членов 1](image/3.jpg){ #fig:003 width=70% }

![Определение вектора n и вычисление членов 2](image/4.jpg){ #fig:004 width=70% }

![Определение вектора n и вычисление членов 3](image/5.jpg){ #fig:005 width=70% }

3. Сумма ряда

![Задание](image/з1.jpg){ #fig:006 width=70% }

![Задание](image/6.jpg){ #fig:007 width=70% }

**Численное интегрирование**

4. Вычисление интегралов

![Задание 2](image/з2.jpg){ #fig:008 width=70% }

![Задание 2](image/7.jpg){ #fig:009 width=70% }

5. Аппроксимирование суммами

![Задание 3](image/з3.jpg){ #fig:010 width=70% }

![Задание 3](image/8.jpg){ #fig:011 width=70% }

![Задание 4](image/з4.jpg){ #fig:012 width=70% }

![Задание 4](image/9.jpg){ #fig:013 width=70% }



# Выводы

Научился использовать Octave с пределами, последовательностями и рядами.
