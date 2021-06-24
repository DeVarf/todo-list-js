# todo-list-js
git init - создание репозитория
git add index.html — добавляет index.html
git add . — добавляет все файлы в индексацию
git commit -m 'commit message' — создает коммит с сообщением
git commit --amend - перезапись коммита
git reset HEAD <file> - удаляет файл из индексации
git restore --staged <file> - удаляет файл из индексации(новая версия)
git restore <file> - не сохранять изменения в файле 
git remote -v - для просмотра подключенных удаленных репозиториев
git remote add <shortname> <url> - добавление удаленного репозитория
git fetch [remote-name] - забирает данные с удаленного репозитория, которых нет на локальном(мерджить нужно в ручную)
git pull [remote-name] - забирает данные с удаленного репозитория, которых нет на локальным(мерджится автоматически)
git push <remote-name> <branch-name> - залить изменения на удаленный репозиторий
git remote rename <prev-name> <new-name> - переименнование удаленного репозитория
git remote remove <name> - удаление удаленного репозитория
git branch <branch-name> - создание новой ветки
git checkout <branch-name> - переключение на новую ветку
git checkout -b <newbranchname> - создать и сразу же переключиться на новую ветку
git switch <branch-name> - переключение на новую ветку
git switch -c <newbranchname> - создать и сразу же переключиться на новую ветку
git switch - dернуться к предыдущей извлечённой ветке
git branch -d <branch-name> - удаление ветки
git merge <branch-name> - мерджит текущую ветку с введенной
git branch -v - просмотр последнего коммита на каждой из веток
git branch --merged - просмотр веток, которые уже замерджены в текущую ветку
git branch --no-merged - просмотр веток, которые еще не замерджены в текущую ветку
git branch --move <old-name> <new-name> - смена имени ветки
git checkout -b <branch> <remote>/<branch> - отслеживание ветки на удаленном сервере
git branch -u origin/serverfix - переключение существующей ветки на отслеживание ветки с удаленного репозитория
git branch -vv - просмотр отслеживающихся веток
git push origin --delete <branch-name> - удаление ветки на удаленном репозитории
git push --set-upstream origin <new branch-name> - загрузка локальной ветки на удаленный репозиторий(создаст там ветку и свяжет с локальной)



