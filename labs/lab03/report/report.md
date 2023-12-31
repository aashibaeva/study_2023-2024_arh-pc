---
## Front matter
title: "Шаблон отчёта по лабораторной работе №3"
subtitle: "Дисциплина: архитектура компьютера"
author: "Шибаева Александра Алексеевна"

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

Целью данной лабораторной работы является освоение процедуры оформле- ния отчетов с помощью легковесного языка разметки Markdown.

# Задание

  1. Установка необходимого ПО
  2. Заполнение отчета по выполнению лабораторной работы №4 с помощью языка разметки Markdown
  3. Задание для самостоятельной работы# Теоретическое введение

# Теоретическое введение

Markdown - легковесный язык разметки, созданный с целью 
обозначения форматирования в простом тексте, с максимальным
 сохранением его читаемости человеком, и пригодный для машинного 
преобразования в языки для продви- нутых публикаций. Внутритекстовые
 формулы делаются аналогично формулам LaTeX. В Markdown вставить
 изображение в документ можно с помощью непосредственного
 указания адреса изображения. Синтаксис Markdown для встроенной 
ссылки состоит из части [link text], представляющей текст гиперссылки,
 и ча- сти (file-name.md) – URL-адреса или имени файла, на который
 дается ссылка. Markdown поддерживает как встраивание фрагментов
 кода в предложение, так и их размещение между предложениями в виде 
отдельных огражденных бло- ков. Огражденные блоки кода — это простой способ выделить синтаксис для фрагментов кода.                                                                               |

# Выполнение лабораторной работы

Описываются проведённые действия, в качестве иллюстрации даётся ссылка на иллюстрацию (рис. @fig:001).

![Название рисунка](image/placeimg_800_600_tech.jpg){#fig:001 width=70%}

# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
