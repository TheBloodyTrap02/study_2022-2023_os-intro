---
## Front matter
title: "Отчёт по второму этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Петросян Эмиль Манукович"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


# Цель работы
- Добавить к сайту данные о себе.

# Задание
- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography)
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:
- Управление версиями. Git.
- Непрерывная интеграция и непрерывное развертывание (CI/CD).


# Выполнение второго этапа индивидуального проекта

1. Для размещения фотографии зашли в “authors” -> “admin” и добавили
фотографию. (рис. [-@fig:001]), (рис. [-@fig:002])

![Аватар](image/1.png){ #fig:001 width=70%}

![Аватар](image/2.png){ #fig:002 width=70%}

2. Добавили краткое описание владельца сайта, информацию о интересах, образовании. В этой же папке открыли файл “md” и изменили информацию. (рис. [-@fig:003]), (рис. [-@fig:004]), (рис. [-@fig:005])

![Био](image/3.png){ #fig:003 width=70%}

![Био](image/4.png){ #fig:004 width=70%}

![Био](image/5.png){ #fig:005 width=70%}

3. Далее добавили пост недели и пост по выбору. Перешли в папку “contents”
-> “post” и добавили необходимую информацию. (рис. [-@fig:006]), (рис. [-@fig:007]), (рис. [-@fig:008]), (рис. [-@fig:009]), (рис. [-@fig:010]), (рис. [-@fig:011])

![Пост недели](image/6.png){ #fig:006 width=70%}

![Пост недели](image/7.png){ #fig:007 width=70%}

![Пост недели](image/8.png){ #fig:008 width=70%}

![Пост по выбору](image/9.png){ #fig:009 width=70%}

![Пост по выбору](image/10.png){ #fig:010 width=70%}

![Пост по выбору](image/11.png){ #fig:011 width=70%}

4. Загрузили все изменения на гитхаб. (рис. [-@fig:012])

![Гитхаб](image/12.png){ #fig:012 width=70%}


# Выводы

В ходе выполнения первого этапа индивидуального проекта были изучены способы изменения информации на сайте и создания постов.
