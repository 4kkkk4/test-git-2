1. git status
2. git add [files] - добавляет файлы в stage (промежуточную область) для последующей отправки на репозиторий
3. git commit -m "comment"  - добавляет комментарий
4. git log   -подробная инфа о коментариях
5. git log --oneline   -краткая запись о коментах
6. git push [rep_link] [branch_name]  -команда добавить локальные файлы в репозиторий в скобках [ссылка на репозиторий] и [имя ветки]
7. git remote -v   -этой командой можно посмотреть ссылку на репоз-й
8. git branch    -так можно узнать имя ветки репоз-я (команда показывает все ветки проекта)
9. git push origin master  -получили команду для отправки локальных данных на удаленный репозиторий
Если ошибочно добавили файл в промежуточную область то его можно удалить из пром области след командой:
10. git reset |имя Файла|
11. git diff  -показывает все строки которые изменяли или добавляли
12. git diff |имя Файла| показывает измы определенного файла
13. git reset --hard  -отменяет все изменения в локальном проекте и очищает гит статус
14. git branch |имя новой ветки|  -команда для добавления новой ветки
15. git checkout |имя ветки на которую переключаемся| -команда для переключения на другую ветку

16. git pull origin master команда для переноса(слияния) ветки из удаленного репозитория на локольный проект