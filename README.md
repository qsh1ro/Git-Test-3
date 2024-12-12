1. git status
2. git add README.md index.html index.js
3. git commit -m "comment" - commit = запись
4. git log(показывает подробную информацию о наших записях) / git log --oneline(показывает краткую запись о коммитах)
5. git push [rep_link] [branch_name] / git push origin master 

проверка ветки(branch) - git branch

чтобы убрать файл из записи(stage) используем команду reset:
git reset (index.html)

git diff - показывает изменения в файлах(для всех)
git diff index.html - для определенного

git reset --hard - уберет все изменения или вернет все на место 

файл .gitignore - нужен для игнорирования отправки файлов в репозиторий 
если файл отображен серым то он не будет загружаться в репозиторий