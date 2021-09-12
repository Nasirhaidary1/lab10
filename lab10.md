# РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
## Факультет физико-математических и естественных наук
### *ОТЧЕТ*
### *ПО ЛАБОРАТОРНОЙ РАБОТЕ №5*

*дисциплина: Операционные системы*

Студент: Хайдари Ахмад Насир
Группа: НБИбд-01-20

### **МОСКВА** 

#### 2021 г


### Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

## *Введение*

### *Что такое Emacs?*

Emacs — один из наиболее мощных и широко распространённых редакторов, используемых в мире Unix. По популярности он соперничает с редактором vi и его клонами. В зависимости от ситуации, Emacs может быть:

> текстовым редактором;
> программой для чтения почты и новостей Usenet;
> интегрированной средой разработки (IDE);
> операционной системой;
> всем, чем угодно.

Всё это разнообразие достигается благодаря архитектуре Emacs, которая позволяет расширять возможности редактора при помощи языка Emacs Lisp. На языке C написаны лишь самые базовые и низкоуровневые части Emacs, включая полнофункциональный интерпретатор языка Lisp. Таким образом, Emacs имеет встроенный язык программирования, который может использоваться для настройки, расширения и изменения поведения редактора. В действительности, большая часть того редактора, с которым пользователи Emacs работают в наши дни, написана на языке Lisp.

Первая версия редактора Emacs была написана в 70-х годах 20-го столетия Richard Stallman (Ричардом Столманом) как набор макросов для редактора TECO. В дальнейшем, уже будучи основателем Фонда Свободного программного обеспечения Free Software Foundation и проекта GNU, Столман разработал GNU Emacs в развитие оригинального Emacs и до сих пор сопровождает эту программу.


## Порядок работы.

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором emacs.
3. Выполнить упражнения.
4. Ответить на контрольные вопросы.

---   
   ### Ход работы:

1. Открыть emacs.

<a href="https://wampi.ru/image/RAweeqV"><img src="https://ic.wampi.ru/2021/09/12/1cccffce62060bcb6.png" alt="1cccffce62060bcb6.png" border="0"></a>

2. Создать файл lab07.sh с помощью комбинацииCtrl-xCtrl-f(C-x C-f).
3. <a href="https://wampi.ru/image/RAwe2ck"><img src="https://ic.wampi.ru/2021/09/12/293527d0894606659.png" alt="293527d0894606659.png" border="0"></a>3. Наберите текст:
>#!/bin/bash
 HELL=Hello
 function hello {
 LOCAL HELLO=World
 echo $HELLO
 }
 echo $HELLO
 hello


<a href="https://wampi.ru/image/RAwA69g"><img src="https://ia.wampi.ru/2021/09/12/4f427f2da5bd0c08e.png" alt="4f427f2da5bd0c08e.png" border="0"></a>


4. Сохранить файл с помощью комбинацииCtrl-xCtrl-s(C-x C-s).
<a href="https://wampi.ru/image/RAwqgqQ"><img src="https://ia.wampi.ru/2021/09/12/54d87890969142ab5.png" alt="54d87890969142ab5.png" border="0"></a>

5. роделать с текстом стандартные процедуры редактирования, каждое действиедолжно осуществляться комбинацией клавиш.
 - 1. Вырезать одной командой целую строку (С-k).
<a href="https://wampi.ru/image/RAwqTYc"><img src="https://ia.wampi.ru/2021/09/12/6da76fff9a1ed17f2.png" alt="6da76fff9a1ed17f2.png" border="0"></a>

- 2. Вставить эту строку в конец файла (C-y).
- <a href="https://wampi.ru/image/RAwqmNf"><img src="https://ia.wampi.ru/2021/09/12/7.png" alt="7.png" border="0"></a>


- 3. Выделить область текста (C-space).

- 4. Скопировать область в буфер обмена (M-w).
- 5. Вставить область в конец файла.
<a href="https://wampi.ru/image/RAwqwfk"><img src="https://ia.wampi.ru/2021/09/12/8.png" alt="8.png" border="0"></a>

- 6. Вновь выделить эту область и на этот раз вырезать её (C-w).
- <a href="https://wampi.ru/image/RAwq3Cg"><img src="https://ic.wampi.ru/2021/09/12/90aa88d9d5928f7ec.png" alt="90aa88d9d5928f7ec.png" border="0"></a>
- - 7. Отмените последнее действие (C-/).

<a href="https://wampi.ru/image/RAwq8Kt"><img src="https://ia.wampi.ru/2021/09/12/107cebeeeb95b774df.png" alt="107cebeeeb95b774df.png" border="0"></a>


6. Научитесь использовать команды по перемещению курсора.6.1.  
- 1. Переместите курсор в начало строки (C-a).

<a href="https://wampi.ru/image/RAwqPVH"><img src="https://ic.wampi.ru/2021/09/12/1148d84ff2bdb72013.png" alt="1148d84ff2bdb72013.png" border="0"></a>

- 2.Переместите курсор в конец строки (C-e).

<a href="https://wampi.ru/image/RAwq8Kt"><img src="https://ia.wampi.ru/2021/09/12/107cebeeeb95b774df.png" alt="107cebeeeb95b774df.png" border="0"></a>

- 3.Переместите курсор в начало буфера (M-<).

<a href="https://wampi.ru/image/RAwqCVn"><img src="https://ic.wampi.ru/2021/09/12/1308630a8f9696d05c.png" alt="1308630a8f9696d05c.png" border="0"></a>
  

  - 4.Переместите курсор в конец буфера (M->).
<a href="https://wampi.ru/image/RAwqtPQ"><img src="https://ia.wampi.ru/2021/09/12/14747b7a0c9aaa03e6.png" alt="14747b7a0c9aaa03e6.png" border="0"></a>

7. Управление буферами.
 - 1. Вывести список активных буферов на экран (C-x C-b).

<a href="https://wampi.ru/image/RAwB5Dt"><img src="https://ia.wampi.ru/2021/09/12/1567f378aff07ee6bc.png" alt="1567f378aff07ee6bc.png" border="0"></a>

- 2. Переместитесь во вновь открытое окно (C-x) o со списком открытых буфе-ров и переключитесь на другой буфер.

<a href="https://wampi.ru/image/RAwB6EE"><img src="https://ic.wampi.ru/2021/09/12/1633e369ee6f2f8feb.png" alt="1633e369ee6f2f8feb.png" border="0"></a>

- 3. Закройте это окно (C-x 0).
- <a href="https://wampi.ru/image/RAwBGWY"><img src="https://ic.wampi.ru/2021/09/12/17.png" alt="17.png" border="0"></a>

4 Теперь вновь переключайтесь между буферами, но уже без вывода их спискана экран (C-x b).

<a href="https://wampi.ru/image/RAwBin8"><img src="https://ic.wampi.ru/2021/09/12/18.png" alt="18.png" border="0"></a>


 8.  Управление окнами.
  - 1. Поделите фрейм на 4 части: разделите фрейм на два окна по вертикали(C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2)
  <a href="https://wampi.ru/image/RAwBTEI"><img src="https://ia.wampi.ru/2021/09/12/19.png" alt="19.png" border="0"></a>

  <a href="https://wampi.ru/image/RAwBvOV"><img src="https://ia.wampi.ru/2021/09/12/20.png" alt="20.png" border="0"></a>


  - 2. В каждом из четырёх созданных окон откройте новый буфер (файл) и вве-дите несколько строк текста.
<a href="https://wampi.ru/image/RAwBAgH"><img src="https://ic.wampi.ru/2021/09/12/21.png" alt="21.png" border="0"></a>


9.  Режим поиска.
- 1. Переключитесьврежимпоиска(C-s)инайдитенесколькослов,присутствующих в тексте.

<a href="https://wampi.ru/image/RAwBH0s"><img src="https://ia.wampi.ru/2021/09/12/22.png" alt="22.png" border="0"></a>

- 2. Переключайтесь между результатами поиска, нажимаяC-s.
  <a href="https://wampi.ru/image/RAwE5Zl"><img src="https://ic.wampi.ru/2021/09/12/23d34bc09b8e7f93da.png" alt="23d34bc09b8e7f93da.png" border="0"></a>


  - 3. Выйдите из режима поиска, нажав (C-g).

<a href="https://wampi.ru/image/RAwE37E"><img src="https://ia.wampi.ru/2021/09/12/24.png" alt="24.png" border="0"></a>


- 4. Перейдите в режим поиска и замены (M-%), введите текст, который следуетнайти и заменить, нажмитеEnter, затем введите текст для замены. После то-го как будут подсвечены результаты поиска, нажмите!для подтверждениязамены.

<a href="https://wampi.ru/image/RAwEPq6"><img src="https://ic.wampi.ru/2021/09/12/25.png" alt="25.png" border="0"></a>

<a href="https://wampi.ru/image/RAwUYNY"><img src="https://ic.wampi.ru/2021/09/12/27.png" alt="27.png" border="0"></a>

<a href="https://wampi.ru/image/RAwUMKr"><img src="https://ia.wampi.ru/2021/09/12/28.png" alt="28.png" border="0"></a>

<a href="https://wampi.ru/image/RAwUgqI"><img src="https://ia.wampi.ru/2021/09/12/29.png" alt="29.png" border="0"></a>

- 5. Попробовать другой режим поиска, нажав M-s o. Он отличается от обычного режима тем, что при поиске указывает номера строк в которых найдено введённое слово и выделяет их цветом. В обычном режиме выделение цветом появляется, только когда нужно подтвердить замену.
  
  <a href="https://wampi.ru/image/RAwUf8V"><img src="https://ia.wampi.ru/2021/09/12/30.png" alt="30.png" border="0"></a>


  ### *Вывод*
Познакомился с операционной системой Linux, получил практические навыки работы с редактором Emacs.

