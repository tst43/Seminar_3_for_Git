## Всем привет, это файл(туториал) по командам git(программа для контроля версии)

## Как инициализировать GIT
**Чтобы инициализировать репозитоорий, необходимо прописать в терминале следующую команду:**

```
git init
```

## Создание коммитов


### Git add
Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория 
Для того, чтобы посмотреть состояние репозитория используйте команды *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли изменения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(Фиксация или сохранение) необходимо выполнить выполнить команду *git commit*. Выполняется она так:
```
git commit -a -m 'Комментарий коммита'

                  Или

git commit -am 'Комментарий коммита'
``` 

## Дополнитьельные полезные команды

### Просмотр изменений между текущим состоянием и крайним коммитом
В Git есть возможность просмотреть изменения файла между текущей версией и крайним коммитом с помощью команды:
```
git diff
```



# Туториал(справка) для работы с языком разметки MarkDown



## Заголовки 








## Цитаты

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:

> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");

## Исходный код








## Таблицы 