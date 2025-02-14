# Инструкция для работы с Markdown

## Основные понятия

**Коммит**-версия файла

**Ветка**-параллель создания файла позволяет создавать коммиты независимые друг от друга (можно работать разным людям над одним и тем же файлом)

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*). Например, *вот так*.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звёздочками (**). Например, **вот так**.

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*). Например, вот так:

* Элемент 1
* Элемент 2

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:

1. Элемент а
2. Элемент б

## Изображения 

Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет.](%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.jpeg)

## GIT 

**GIT** - самая популярная система контроля версий, но не единственная. Алгоритм работы подобных систем схож.
## Основные команды

**git status** - проверка на инициализированность папки.

**git init** - инизиализация в git папке, создается скрытый файл .git, в котором сохраняются все данные о изменении файла, также создает главную ветку.

**git add** - команда добавляет файлы с сохраненными изменениями к текущей ветке "коммитов".

*git add .* - добавление всех файлов в коммит.

*git add namefill* - добавление файла по имени namefill.

**git log** - команда позволяет посмотреть все коммиты в данной ветке коммитов.

*git log --all* - показывает все коммиты даже, если вы находитесь не на последнем коммите.

*git log --graph* - вывод структуры.

**git checkout** - команда позволяет переключатся между коммитами.

**git diff** - различия между текущем файлом и сохраненным.

*git commit - m "..."* - комментарий к коммиту.

**git branch** - создание новой ветки в коммите.

*git branch -d "Название ветки"* - удаление ветки.

**git merge** - слияние черновиков в чистовик.



![Water](%D0%B2%D0%BE%D0%B4%D0%B0.jpg)

## Ссылки в тексте

Ссылки на [GB.ru](https://gb.ru/)

# Работа с удаленными репезиториями

## GitHub 

* Предоставляет Microsoft
* Самый популярный сервис git
* Много полезных функций
* Огромный архив различных функций

## Основные команды

**git clone** - команда, не только загружающая все изменения, но и пытающаяся слить все ветки на локальный компьютер и в удаленном репезитории.

**git pull** - команда, позволяющая скачать все из текущего репозитория и автоматически сделать merge с нашей версией.

**git push** - команда, позволяющая отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории. 

## Как настроить совместную работу

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. "Подружить" ваш локальный и удаленный репозитории
4. Отправить (push) ваш локальный репозиторий в удаленный (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удаленном репозитории
5. "Провести изменения с другого компьютера"
6. Выкачать (pull) актуальное состояние из удаленного репозитория.

## Как сделать pull request

1. Делаем fork (ответвление) репозитория
2. Делаем git clone своей версии репозитория
3. Создаем новую ветку и в НЕЕ вносим свои изменения
4. Фиксируем изменения (делаем крммиты)
5. Отправляем свою версию в свой GitHub
6. На сайте [GitHub](https://github.com) нажимаем кнопку pull request
