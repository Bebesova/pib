## 1. Создать учетную запись на ресурсе github.com
```
   git config --global user.name "Bebesova"
   git config --global user.email "zevaliheim@gmail.com"
```
## 2. Создать на ресурсе github.com репозиторий для выполнения практической работы
 git init
## 3. Создать папку для работы с Git. 

## 4. Создать локальный репозиторий в текущей папке. 
```
git clone thhps://github.com/bebesova/pib.git
```
## 5. Добавьте туда пустой текстовый документ. 
```
git add text.txt
```
## 6. Сформируйте этот документ, создавая commit для каждого абзаца, не  менее 5 абзацев. 
## 7. Посмотреть статус текущего репозитория. 
```
git status
```
![image](https://github.com/Bebesova/pib/blob/main/Screenshot_7.png)

## 8. Добавить файл. 
```
git add Newtext.txt
```
## 9. Создать коммит, указать для него комментарий. 
```
$ git commit -m "супер новый текстовый файл 3000"
```
## 10.Посмотреть протокол коммитов.
![image](https://github.com/Bebesova/pib/blob/main/Screenshot_9.png)
 
## 11.Посмотреть изменения в файле по сравнению с последним коммитом.  
```
git log -n
commit 20f09aba418a73d2ced73a2cf1d97e64623bb76d (HEAD -> main)
Author: Bebesova <Zevaliheim@gmail.com>
Date:   Wed Mar 13 13:55:35 2024 +0500

    Супер новый текстовый файл 3000

diff --git a/Newtext.txt b/Newtext.txt
new file mode 100644
index 0000000..e69de29

commit 0d1cdf394961ebdd574b60666545442c2196be4a (origin/main, origin/HEAD)
Author: Bebesova <Zevaliheim@gmail.com>
Date:   Wed Mar 13 13:50:12 2024 +0500

    пятый

diff --git a/text.txt b/text.txt
index b178657..85954ea 100644
--- a/text.txt
+++ b/text.txt
@@ -1,4 +1,5 @@
 1
 2
 3
-4
\ No newline at end of file
+4
+5
\ No newline at end of file
```
## 12.Убрать изменения относительно последнего коммита из файла. 
```
git restore Newtext.txt
```
## 13.Просмотреть существующие ветки. 
```
git branch
```
## 14.Создать новую ветку. 
```
 git branch NewBranch
```
## 15.Переключиться на другую ветку. 
```
git checkout NewBranch
```
## 16.Создать новую ветку и сразу же переключиться на нее. 
```
git checkout -b supernewbranch
```
##17.Удалить ветку.  
для выполнения следующего действия необходимы было поменять ветвь 
```
git branch -d supernewbranch
```
18.Добавить (merge) изменения из указанной ветки в текущую. 
```
$ git merge main
```
## 19. Создать конфликт. 
добавила в файл текста
```
git add text.txt

git commit -m "ДОБАВЛЕН МЕГА ОБЗАЦ"
[main 5dc3ac7] ДОБАВЛЕН МЕГА ОБЗАЦ
 1 file changed, 2 insertions(+), 1 deletion(-)
```
![image](https://github.com/Bebesova/pib/blob/main/Screenshot_12.png)

## 20 Посмотреть в каких файлах есть конфликты. 
![image](https://github.com/Bebesova/pib/blob/main/Screenshot_13.png)
## 21.Устранить конфликты. 
Редактируем конфликтный фаил 
```
git add text.txt

git commit -m " Это все мега абзац!!"
git commit -m " Это все мега абзацgit add text.txt"
[NewBranch 8f7ccb1]  Это все мега абзацgit add text.txt
```
## 22.Переключиться на указанный коммит. 
![image](https://github.com/Bebesova/pib/blob/main/Screenshot_14.png)
## 23.Сделать ребазирование (rebase) текущей ветки. 
```
git rebase main
```
## 24.Удалить ветку.
```
git branch -D newbranch
```
## 25.Пропустить текущий конфликтный коммит и перейти к следующему. 
```
git merge --abort
```
## 26.Отправить изменения из локального репозитория для указанной ветки в удаленный (дистанционный). 
## 27.Забрать изменения из репозитория, для которогобыли созданы удаленные ветки по умолчанию. 

## 28.Забрать изменения удаленной ветки из репозитория основной ветки по умолчанию. 

## 29.Создать копию репозитория.

