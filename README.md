git init # создали репозиторий 

rm -rf .git # удалили подпапку .git  Если вы случайно сделали Git-репозиторием не ту папку, её можно «разгитить». 

git status # Проверить состояние репозитория 

git add #Подготовить файлы к сохранению

touch todo.txt #Создать файл todo.txt 

git add --all # подготовили к сохранению все файлы в репозитории

git add readme.txt #добавлять файл по одному

git add . # добавить всю текущую папку

git commit -m ‘Мой первый коммит!’ 

git log #Просмотреть историю коммитов

git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git #Привязать удалённый репозиторий к локальному 

git remote -v #Убедиться, что репозитории связаны

git push #Отправить изменения на удалённый репозиторий

git push -u origin main #В первый раз эту команду нужно вызвать с флагом -u и параметрами origin (имя удалённого репозитория) и main или master (название текущей ветки). Флаг -u свяжет локальную ветку с одноимённой удалённой. Как вы связывали локальный и удалённый репозитории в предыдущем уроке, так же и здесь нужно дополнительно связать ветки.

