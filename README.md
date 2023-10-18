# Honework file

# Инструкция по работе с Git  и удаленными репозиториями

![foto 1](456.jpeg)


##  Основные команды Git

Основные команды следующие:![foto 2](39.png) 



* Команда Git init

Команда git init создает новый репозиторий Git. С ее помощью можно преобразовать существующий проект без управления версиями в репозиторий Git или инициализировать новый пустой репозиторий. Большинство остальных команд Git невозможно использовать без инициализации репозитория, поэтому данная команда обычно выполняется первой в рамках нового проекта.


* Команда Git add

Команда git add :/ добавляет в индекс все файлы независимо от того, в какой директории вы находитесь.
Сделать коммит — git commit -m "Комментарий к коммиту" — фиксирует изменения. До выполнения этой команды локальные изменения никуда не запишутся.
Нужно правильно разбивать изменения и давать полные комментарии к коммитам.


* Команда Git commit

Сделать коммит — git commit -m "Комментарий к коммиту" — фиксирует изменения. До выполнения этой команды локальные изменения никуда не запишутся. Нужно правильно разбивать изменения и давать полные комментарии к коммитам. Посмотреть историю коммитов — git log. Выводит список всех коммитов. У этой команды есть разные опции, самая используемая из них — --oneline.


* Команда Git branch

` git branch` – это команда Git для управления ветками. Используйте эту метку для обозначения всех вопросов, связанных с ветками, их созданием, структурой, управлением и удалением. Общие сведения. git branch – это команда для управления ветками в репозитории Git. Ветка в Git'е — это просто «скользящий» указатель на один из коммитов. Когда вы создаёте новые коммиты, указатель ветки автоматически сдвигается вперёд, к вновь созданному коммиту.



* Комманда Git Log

Команда git log используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. По умолчанию, она показывает лишь историю текущей ветки, но может быть настроена на вывод истории других, даже нескольких сразу, веток. Также её можно использовать для просмотра различий между ветками на уровне коммитов.




* Команда Git checkout

1.  Команда git checkout позволяет перемещаться между ветками, созданными командой git branch. 
2. При переключении ветки происходит обновление файлов в рабочем каталоге в соответствии с версией, хранящейся в этой ветке, а Git начинает записывать все новые коммиты в этой ветке.






