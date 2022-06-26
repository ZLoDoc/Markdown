# Домашняя работа

### по теме "Введение в контроль версий"
##### ***Выполнил: Пшеничников Виталий***

![Avatar](https://s.gravatar.com/avatar/df6d0d936bf3d7768276098f0abb5e7c?s=80 "Мой аватар")



## Данная работа выполнена при использовании синтаксиса  ***Markdown*** 

## *Markdown – язык разметки, который позволяет форматировать текст.* 

# **Заголовки**
* Для выделения заголовка используется символ в начале строки "#".
В зависимости от количества символов будут создаваться разные уровни заголовков.

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня

# Разметка текста

* Для написания текста курсивом, необходимо текст поместить между символами "*" 
	- Пример: *Курсив*

* Для выделения текста полужирным, необходимо текст поместить между символами **  
	- Пример: **Полужирный**

* Для  написания текстом полужирным курсивом, необходимо текст поместить между символами "***" 
	- Пример: ***Полужирнуй курсив***

* Для написания зачеркнутого текста, необходимо текст поместить между символами "~~" 
	- Пример ~~Перечеркнутый~~
	

# Разделение текста

* Для этого необходимо поместить на следующей строке знак " *** "

Пример:

### Разделительная черта 
***

# Списки

+ Для нумерации списков, достаточно просто проставлять порядковый № с точкой.

1. Один
2. Два
3. Три

* Или поставить символ " * " или " - " или " + " для обозначения пункта точкой.

* Один
* Два
* Три


# Цитаты

* Для обозначения цитат в языке используется символ ">" и в  Markdown  выглядят следующим образом:

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

Вложение цитаты в цитату выглядит следующим образом:
> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования

##### Уровень цитирования не может превышать 15-й.


# Таблицы

* Для создания таблицы в Markdown мы используем тире " - " и вертикальные полосы " | " для разделения строк и столбцов.

* В первой строке таблицы мы строим заголовок, разделяя эту строку тремя или более дефисами " --- ", чтобы процессор Markdown понимал форматирование.

* Разделение столбцов выполняется с помощью вертикальной черты " | ", которую программисты также называют pipe.

| Заголовок  | Заголовок   |
| ------- | -------- |
| Текст   | Текст    |
| Текст   | Текст    |

* Вертикальные полосы | на концах стола используются чисто для косметических целей, то есть вы можете создать стол без боковых планок.

Заголовок  | Заголовок
------- | --------
Текст   | Текст
Текст   | Текст

* Markdown позволяет выровнять содержимое столбца таблицы по левому, правому или центру.

* Чтобы выровнять содержимое по левому краю в таблице Markdown, поместите двоеточие : перед дефисами " --- ", разделяющими строку заголовка.

* Чтобы выровнять текст по правому краю в таблице Markdown, вставьте двоеточие : после тире " --- ", разделяющих строку заголовка.

* Чтобы выровнять содержимое столбца по центру в таблице Markdown, добавьте двоеточие : до и после тире, разделяющих строку заголовка.


| Фрукты  | Ягоды | Овощи |
|    ---: |    :----: |    :--- |
| кешью    | Малина   | Морковь |
| яблоко    | Клубника | Горох |




# GIT

Программа Git берёт на себя контроль версий
проекта и позволяет переключаться между
ними. Обратите внимание: Git хранит не файлы
целиком, а отличия между ними.
* Это позволяет
экономить память. Автор программы — _Линус
Торвальдс_, создатель ОС Linux.

## Команды Git

Осваивать Git проще процессе редактирования текстовых файлов.
Все команды задаём при помощи написания кода в терминале.
Прежде чем создавать репозиторий и инициализировать Git, проверим текущую установленную
версию пограммы. Для этого в терминале введём команду:
 
 ***git --version***
 
 Если Git установлен на компьютер, вы увидите его текущую версию.
Программа использует мнемонические команды, которые легко запомнить, если знать английский язык.

## Создание Git-репозитория:
Берём локальный каталог, который не находится под версионным контролем и превращаем его в репозиторий.
Клонируем существующий репозиторий из любого места.

* Команда ***git init***
Инициализация: указываем папку, в которой
git начнёт отслеживать изменения
В папке создаётся скрытая папка .git

* Команда ***git status***
Показывает текущее состояние гита, есть ли изменения, которые нужно закоммитить(сохранить)

* Команда ***git add***
добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита. Эта команда дается после добавления файлов. Писать название целиком не обязательно: терминал дозаполнит данные автоматически.

* Команда ***git commit -m (-m – параметр позволяющий оставить коммент)***
зафиксировать или сохранить
По умолчанию git commit использует лишь этот индекс, так что вы можете использовать git add для сборки слепка вашего следующего коммита.
Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.

* Команда ***git log*** 

Журнал изменений
Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений

* Команда ***git checkout***
Переключение между версиями.
Для работы нужно указать не только интересующий вас коммит, но и вернуться в тот, где работаем, при помощи команды git checkout master

* Команда ***git diff***
Показывает разницу между текущим файлом и сохранённым 
Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений

# The End