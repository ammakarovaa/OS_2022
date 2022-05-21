---
## Front matter
title: "Отчёт по четвёртому этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Макарова Анастасия Михайловна"

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

1. Добавить к сайту ссылки на научные и библиометрические ресурсы.

2. Сделать пост по прошедшей неделе.

3. Добавить пост на тему по выбору: "Оформление отчёта" или "Создание презентаций" или "Работа с библиографией".

# Выполнение лабораторной работы

1. Зарегистрируемся на соответствующих ресурсах (Рис.1-7):

* eLibrary : https://elibrary.ru/ (Рис. 1);

![Рис.1](image/1.jpg){ #fig:001 width=70% }

* Google Scholar : https://scholar.google.com/ (Рис. 2);

![Рис.2](image/2.jpg){ #fig:001 width=70% }

* ORCID : https://orcid.org/ (Рис. 3);

![Рис.3](image/3.jpg){ #fig:001 width=70% }

* Mendeley : https://www.mendeley.com/ (Рис. 4);

![Рис.4](image/4.jpg){ #fig:001 width=70% }

* ResearchGate : https://www.researchgate.net/ (Рис. 5);

![Рис.5](image/5.jpg){ #fig:001 width=70% }

* Academia.edu : https://www.academia.edu/ (Рис. 6);

![Рис.6](image/6.jpg){ #fig:001 width=70% }

* arXiv : https://arxiv.org/ (Рис. 7);

![Рис.7](image/7.jpg){ #fig:001 width=70% }

* github : https://github.com/ammakarovaa/OS_2022.

Затем открываем файл content/authors/admin/_index.md и редактрируем информацию, добавляем ссылки на академические ресурсы и их иконки из пакета Academic (Рис. 8). Выгружаем изменения на сайт (Рис. 9).

![Рис.8](image/8.png){ #fig:001 width=70% }

![Рис.9](image/9.png){ #fig:001 width=70% }

2. Сделаем пост по прошедшей неделе. Для создаем новый файл с помощью командной строки: hugo new post/post5.md (Рис. 10). Открываем созданный нами файл и редактируем его, внося информацию о себе, а именно: о проведенном нами времени на прошедшей неделе, также изменяем название, подзаголовок, автора, добавляем тэг и категорию (Рис. 11). Отправляем изменения на наш сайт и открываем созданный пост (Рис. 12).

![Рис.10](image/10.png){ #fig:001 width=70% }

![Рис.11](image/11.png){ #fig:001 width=70% }

![Рис.12](image/12.png){ #fig:001 width=70% }

3. Добавим пост на тему по выбору. Я выбрала тему: "Создание презентаций". Как и в предыдущем пункте, создаем с помощью командной строки и команды hugo new post/post6.md новый файл и открываем его (Рис. 13). Редактируем его (Рис. 14). Отправляем изменения на сайт (Рис. 15, 16).

![Рис.13](image/13.png){ #fig:001 width=70% }

![Рис.14](image/14.png){ #fig:001 width=70% }

![Рис.15](image/15.png){ #fig:001 width=70% }

![Рис.16](image/16.png){ #fig:001 width=70% }

# Выводы

В ходе выполнения четвертого этапа по созданию сайта я научилась добавлять ссылки на различные ресурсы и менять иконки, а также написала новые посты.

