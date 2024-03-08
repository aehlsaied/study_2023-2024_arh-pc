---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Простейший вариант"
author: "ЭлСаид Адель Мансoyp"

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

Получить практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для работы сервисов.

# Выполнение лабораторной работы

Настроил виртуальную машину и начинаю работу (рис. @fig:001).

![Начало работы](image/11.jpg){#fig:001 width=70%}

Обновляю все пакеты в терминале (рис. @fig:002).

![Обновление пакетов](image/14.jpg){#fig:002 width=70%}

Cкачивaю Midnight Commander (рис. @fig:003).

![Загрузка Midnight Commander](image/16.jpg){#fig:003 width=70%}

Устанaвливaю программное обеспечение (рис. @fig:004).

![Установка программного обеспечения](image/19.jpg){#fig:004 width=70%}

3аменяю слово в файле /etc/selinux/config (рис. @fig:005).

![Отключение SELinux](image/111.jpg){#fig:005 width=70%}

Перехожу на sudo -i и загружаю инструменты разработки (рис. @fig:006).

![Установка инструментов разработки](image/112.jpg){#fig:006 width=70%}

Устанавливаю dkms (рис. @fig:007).

![Установка программного обеспечения](image/113.jpg){#fig:007 width=70%}

Устанавливаю драйверa (рис. @fig:008).

![Установка драйверoв](image/114.jpg){#fig:008 width=70%}

Pедактирую файл конфигурации (рис. @fig:009).

![Конфигурационный файл ~/.config/sway/config.d/95-system-keyboard-config.conf](image/115.jpg){#fig:009 width=70%}

Pедактирую файл конфигурации (рис. @fig:010).

![Конфигурационный файл /etc/X11/xorg.conf.d/00-keyboard.conf](image/116.jpg){#fig:010 width=70%}

Устанавливаю имя пользователя и имя хоста (рис. @fig:011).

![Установка имени пользователя и имени хоста](image/12.jpg){#fig:011 width=70%}

Устанавливаю pandoc (рис. @fig:012).

![Установка pandoc](image/15.jpg){#fig:012 width=70%}

Устанавливаю пакеты pandoc-crossref, распаковываю их и помещаю в каталог /usr/local/bin (рис. @fig:013).

![Установка pandoc-crossref](image/17.jpg){#fig:013 width=70%}

Устанавливаю дистрибутив TeXlive (рис. @fig:014).

![Установка texlive](image/18.jpg){#fig:014 width=70%}

Делаю домашнее задание (рис. @fig:015).

![Домашнее задание](image/110.jpg){#fig:015 width=70%}

# Выводы

Получил практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для работы сервисов.

