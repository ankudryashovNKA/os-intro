---
## Front matter
title: "Отчёт по индивидуальному проекту этап №3"
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

Продолжить наполнение персонального сайта на hugo первоклассным контентом.

# Задание

Заполнить блоки Skills, Experience и Accomplishments на гланой странице сайта, а также добавить пост по прошедшей неделе и пост о легковесных языках разметки

# Выполнение лабораторной работы

Запустим сервер и перейдем на localhost (рис. @fig:001).

![Зайдём на localhost](image/1.jpg){#fig:001 width=70%}

Изменим файл index.md в папке content так, чтобы подстроить его под свои скиллы (рис. @fig:002).

![Изменение блока Skills](image/2.jpg){#fig:002 width=70%}

Теперь поработаем над изменением блока Experience. Добавим информацию об учёбе в школе и начале обучения в ВУЗе (рис. @fig:003).

![Изменение блока Experience](image/3.jpg){#fig:003 width=70%}

Далее персонифицируем блок Accomplishments. Не будем подходить к этому сльшком серьёзно (рис. @fig:004).

![Изменение блока Accomplishments](image/4.jpg){#fig:004 width=70%}

Наконец, напишем два поста. Один про прошлую неделю, второй про легковесные языки разметки. Для этого повторим синтаксис языка Markdown (рис. @fig:005).

![Два новых поста](image/5.jpg){#fig:005 width=70%}

В результате получили такие исходники (рис. @fig:006).

![Исходники двух постов](image/6.jpg){#fig:006 width=70%}

# Выводы

В ходе выполнения этого этапа работы над индивидуальным проектом удалось выполнить все задания. Мы кастомизировали все необходимые блоки главной страниц и добавили два поста на актуальные темы. Сайт живёт и обновляется.

# Список литературы{.unnumbered}

::: {#refs}
:::
