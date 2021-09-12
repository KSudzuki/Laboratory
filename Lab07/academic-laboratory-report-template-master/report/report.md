---
# Front matter
lang: ru-RU
title: "Отчет по лабораторной работе №7"
subtitle: "Графики"
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

Научиться применять Octave с графиками.

# Задание

1. Сделайте отчет по лабораторной работе в формате Markdown.

2. В качестве отчета просьба предоставить отчеты в 3 форматах: pdf,docx и md(в архиве, поскольку он должен содержать скриншоты, Markfile и т.д)


# Выполнение лабораторной работы

#**Графики**

1. Параметрические графики

![Параметрические графики](image/1.jpg){ #fig:001 width=70% }

![Параметрический график](image/2.jpg){ #fig:002 width=70% }

2. Полярные координаты

![Графики в полярных координатах 1](image/3.jpg){ #fig:003 width=70% }

![Графики в полярных координатах 2](image/4.jpg){ #fig:004 width=70% }

![Графики в полярных координатах 3](image/5.jpg){ #fig:005 width=70% }

![Графики в полярных координатах 4](image/6.jpg){ #fig:006 width=70% }

![Графики в полярных координатах 5](image/7.jpg){ #fig:007 width=70% }

3. Графики неявных функций

![Графики неявных функций 1](image/8.jpg){ #fig:008 width=70% }

![Графики неявных функций 2](image/9.jpg){ #fig:009 width=70% }

![Графики неявных функций 3](image/10.jpg){ #fig:010 width=70% }

![Графики неявных функций 4](image/12.jpg){ #fig:011 width=70% }

![Графики неявных функций 5](image/11.jpg){ #fig:012 width=70% }

![Графики неявных функций 6](image/13.jpg){ #fig:013 width=70% }

![Касательная к графику ](image/14.jpg){ #fig:014 width=70% }

4. Комплексные числа

![Комплексные числа 1](image/15.jpg){ #fig:015 width=70% }

![Комплексные числа 2](image/16.jpg){ #fig:016 width=70% }

![Compass](image/17.jpg){ #fig:017 width=70% }

![Compass](image/18.jpg){ #fig:018 width=70% }

![Комплексные числа 3](image/19.jpg){ #fig:019 width=70% }

![Комплексные числа 4](image/20.jpg){ #fig:020 width=70% }

![Комплексные числа 5](image/21.jpg){ #fig:021 width=70% }

![Комплексные числа 6](image/22.jpg){ #fig:022 width=70% }

![Комплексные числа 7](image/23.jpg){ #fig:023 width=70% }

5. Специальные функции

![Специальные функции 1](image/24.jpg){ #fig:024 width=70% }

![Графики n! и gamma(n+1)](image/25.jpg){ #fig:025 width=70% }

![Специальные функции 2](image/26.jpg){ #fig:026 width=70% }

![более точные графики n! и gamma(n+1)](image/27.jpg){ #fig:027 width=70% }




# Выводы

Научился применять Octave с графиками.
