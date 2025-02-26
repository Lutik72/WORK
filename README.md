# Что такое Git
**Git** - это система управления версиями исходногг кода программ. Она позволяет
отслеживать любые изменения в файлах, хранить их версии и оперативно возвращаться в любое созранненое состояние.

# Установка Git и Visual Studio Code
* Установка Git для Windows, MAC, Linux: https://git-scm.com/downloads
* Установка VSCode для Windows, MAC, Linux: https://code.visualstudio.com/Download

При первом использовании Git необходимо представиться.
Для этого нужно ввести в терминале 2 команды:
* git config --global user.name «Ваше имя английскими буквами»
* git config --global user.email «Ваша почта»

# Основные команды Git

* **git init** – инициализация локального репозитория
* **git status** – получить информацию от git о его текущем состоянии
* **git add** – добавить файл или файлы к следующему коммиту
* **git commit** -m “message” – создание коммита.
* **git log** – вывод на экран истории всех коммитов с их хеш-кодами
* **git checkout** – переход от одного коммита к другому
* **git checkout master** – вернуться к актуальному состоянию и продолжить работу
* **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом

# Синтаксис языка Markdown
Язык разметки **Markdown** широко распространен в вебе. На нем пишут readme-файлы и документацию,
а его принципы работы используют для оформления сообщений и публикаций в мессенджерах и социальных сетях

* **#** Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка 
(поддерживается 6 уровней)
* = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого 
(“=”) и второго (“-”) уровней.
* ** **Полужирное начертание** ** или __ __Полужирное начертание__ __
*  **Курсивное начертание* * или 
_ _Курсивное начертание_ _
* *** ***Полужирное курсивное начертание*** ***
* ~~ ~~Зачёркнутый текст~~ ~~
* *Строка – ненумерованные списки, символ “ * ” в начале строки
* 1, 2, 3 … – нумерованные списки
