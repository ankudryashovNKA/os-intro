---
## Front matter
title: "Отчёт по индивидуальному проекту этап №4"
subtitle: "Дисциплина: Операционные системы"
author: "Кудряшов Артём Николаевич"

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

Добавить ссылки на библиографичесие ресурсы (после регистрации на них) и выложить два новых поста.

# Задание

Создать аккаунты на нескольких внешних платформах и привязать их к сайту. Подготовить пост о прошедшей неделе и пост на тему создание презентаций.

# Выполнение лабораторной работы

Запустим сервер и перейдем на localhost (рис. @fig:001).

![Зайдём на localhost](image/1.jpg){#fig:001 width=70%}

Зарегистрируемся на всех необходимых ресурсах (рис. @fig:002).

![Профиль на академии](image/2.jpg){#fig:002 width=70%}

Подберем значки для отображения в листе контактов. Для этого перейдем на специальный сайт с иконками (рис. @fig:003).

![Подбор иконок](image/3.jpg){#fig:003 width=70%}

В результате полуаем такой блок контактов (рис. @fig:004).

![Итоговый результат](image/4.jpg){#fig:004 width=70%}

Получили такой исходный код в файле index.md (рис. @fig:005).

![Исходный код](image/5.jpg){#fig:005 width=70%}

Напишем два поста для нашего сайта: один по прошедшей неделе, другой про создание презентаций (рис. @fig:006).

![Два новых поста](image/6.jpg){#fig:006 width=70%}

# Выводы

В ходе выполнения этого этапа работы над индивидуальным проектом удалось выполнить все задания. Мы кастомизировали все необходимые блоки главной страниц и добавили два поста на актуальные темы. Сайт живёт и обновляется. До встречи на следующем этапе проекта.

# Список литературы{.unnumbered}

::: {#refs}
:::
