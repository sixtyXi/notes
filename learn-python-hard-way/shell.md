<!--@nested-tags:shell,shell/commands-->

# Shell commands

`open -e <filename>` - открыть в режиме редактирования в TextEdit

`chsh -s /bin/bash` - change default shell

## man

`man ls` - показать мануал для программы

## cp

`cp [-r | --recursion] <from> <to>`

## ls

- `-1` - вывод в одну колонку
- `-a` - показать скрытые файлы

Можно использовать wildcards:
`ls image*` - list all files starting with image

## mv

`mv <from> <to>`

## less

пробелом переключаем страницы

## xargs

Using `xargs` allows tools like `echo` and `rm` and `mkdir` to accept standard input as arguments.

`echo 'one two three' | xargs mkdir`

[further reading](https://shapeshed.com/unix-xargs/)

## chmod, chown, stat

`stat <name>` - информация о файле или каталоге

[further reading](https://www.cyberciti.biz/faq/how-to-use-chmod-and-chown-command/)
