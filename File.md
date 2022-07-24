-
sudo cd /путь файла

// очистить терминал 
    clear

// Сохранить изменения в файле 
1) command + S
2) git add <name_file>
3) git commit -m "_"


git config --global user.name "Kosmonaft36"
git config --global user.email kosmonaft2007@ya.ru

 1) Шаг 1 
 - git config --list // провенка на наличие внесыннх данные, с конца 5 и 6 строчка 
 2) Шаг 2
 - git remote add origin https://github.com/Kosmonaft2007/GeekBrains1.git 
 //ссылка с репозитория 
 // - fatal: remote origin already exists. // фатальный: удаленный источник уже существует.
 3) Шаг 3 
 - git push -u origin master 
 // Branch 'master' set up to track remote branch 'master' from 'origin'.
Everything up-to-date // Ветвь "master" настроена для отслеживания удаленной ветви "master" из "origin".
Все в актуальном состоянии
-------

1) git status 
1.1) On banch master // Находится на ветки мастера 
1.2) No commit yet //  нет комментариев 
-
2) git init - создает репазиторий (инициализирует) 
3) git add 
4) git commit

5.0) !!! по окончанию чтения  LOG  нажать на клавишу (Q)
5) git log  // чтение commit
5.1) git log --oneline
-
6) git checkout + № номер комита 2345 
7) !!!! git checkout master // после просмотра комит и векруться к первоначальной нужно уйти на ветку мастер!!!

// переименовать файл 

