Чтобы вывести список всех веок на экран мы используем команду:
 > git branch


 Чтобы создать новую веку, мы используем:


 > git branch branch_name - создается ветка с именем branch_name


 Чтобы удалить ветку, мы используем команду:


 > 1. git branch -d [*имя ветки*] - удаляет ветку с проверкой на merge
 > 2. git branch -D [*имя ветки*] - удаляет ветку без проверки на merge


 Чтобы перейти к необходимой ветке, мы используем команду:


 > git checkout [*имя ветки*]

Чтобы "взять" файл из чужого репозитория на GitHub, мы используем команду:
> 1. git clone [*ссылка*] - перенести репозиторий
> 2. git clone [*ссылка*] [*нзвание папки*] - перенести репозиторий в папку

Чтобы добавить изменения из локального репозитория в GitHub мы используем команду:
> git push

Чтобы "вытянуть" все изменения из GitHub в локальный репозиторий, мы используем команду: