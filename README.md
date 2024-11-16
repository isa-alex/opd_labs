1. Создать приведенное в варианте дерево каталогов и файлов с содержимым. В качестве корня дерева использовать каталог lab0 своего домашнего каталога. Для создания и навигации по дереву использовать команды: mkdir, echo, cat, touch, ls, pwd, cd, more, cp, rm, rmdir, mv.

tree hierarchy with contents


2. Установить согласно заданию права на файлы и каталоги при помощи команды chmod, используя различные способы указания прав.

crobat4: владелец должен читать, записывать директорию и переходить в нее; группа-владелец должна читать и записывать директорию; остальные пользователи должны читать директорию
dragonite: -wxrw--wx
xatu: владелец должен не иметь никаких прав; группа-владелец должна читать файл; остальные пользователи должны читать и записывать файл
rampardos: владелец должен не иметь никаких прав; группа-владелец должна не иметь никаких прав; остальные пользователи должны читать и записывать файл
doduo: rw-r-----
crobat: ------r--
gallade6: r-x--x-wx
hoppip: права 440
slowpoke: владелец должен читать и записывать файл; группа-владелец должна записывать файл; остальные пользователи должны записывать файл
chinchou: права 750
magby6: владелец должен читать, записывать директорию и переходить в нее; группа-владелец должна читать директорию и переходить в нее; остальные пользователи должны записывать директорию и переходить в нее
rufflet: владелец должен читать файл; группа-владелец должна читать файл; остальные пользователи должны читать файл
slowbro: r-x--x-w-
camerupt: владелец должен читать директорию и переходить в нее; группа-владелец должна только переходить в директорию; остальные пользователи должны записывать директорию
togekiss: rw-------
sharpedo0: владелец должен читать файл; группа-владелец должна не иметь никаких прав; остальные пользователи должны не иметь никаких прав
snorunt4: права 664
walrein9: права 400


3. Скопировать часть дерева и создать ссылки внутри дерева согласно заданию при помощи команд cp и ln, а также комманды cat и перенаправления ввода-вывода.

скопировать содержимое файла walrein9 в новый файл lab0/magby6/togekisswalrein
создать символическую ссылку c именем Copy_77 на директорию gallade6 в каталоге lab0
cоздать жесткую ссылку для файла walrein9 с именем lab0/gallade6/slowpokewalrein
скопировать файл snorunt4 в директорию lab0/magby6/slowbro
объеденить содержимое файлов lab0/gallade6/slowpoke, lab0/magby6/togekiss, в новый файл lab0/snorunt4_79
cоздать символическую ссылку для файла snorunt4 с именем lab0/magby6/togekisssnorunt
скопировать рекурсивно директорию magby6 в директорию lab0/crobat4/dragonite


4. Используя команды cat, wc, ls, head, tail, echo, sort, grep выполнить в соответствии с вариантом задания поиск и фильтрацию файлов, каталогов и содержащихся в них данных.

Подсчитать количество символов содержимого файлов в директории crobat4, отсортировать вывод по уменьшению количества, подавить вывод ошибок доступа
Вывести рекурсивно список имен файлов в директории magby6, список отсортировать по имени z->a, добавить вывод ошибок доступа в стандартный поток вывода
Вывести содержимое файлов: xatu, rampardos, doduo, crobat, hoppip, оставить только строки, содержащие "do", ошибки доступа перенаправить в файл в директории /tmp
Вывести три последних элемента рекурсивного списка имен и атрибутов файлов в директории lab0, начинающихся на символ 'c', список отсортировать по убыванию даты доступа к файлу, подавить вывод ошибок доступа
Вывести рекурсивно список имен и атрибутов файлов в директории lab0, содержащих строку "ru", список отсортировать по возрастанию даты доступа к файлу, добавить вывод ошибок доступа в стандартный поток вывода
Вывести три первых элемента рекурсивного списка имен и атрибутов файлов в директории lab0, список отсортировать по убыванию даты изменения записи о файле, ошибки доступа не подавлять и не перенаправлять


5. Выполнить удаление файлов и каталогов при помощи команд rm и rmdir согласно варианту задания.

Удалить файл sharpedo0
Удалить файл lab0/crobat4/xatu
удалить символические ссылки Copy_*
удалить жесткие ссылки lab0/gallade6/slowpokewalre*
Удалить директорию crobat4
Удалить директорию lab0/crobat4/dragonite
