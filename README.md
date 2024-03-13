## 1. Создать учетную запись на ресурсе github.com
```
   git config --global user.name "Bebesova"
   git config --global user.email "zevaliheim@gmail.com"
```
## 2. Создать на ресурсе github.com репозиторий для выполнения практической работы

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
## 8. Добавить файл. 

## 9. Создать коммит, указать для него комментарий. 

## 10.Посмотреть протокол коммитов.
 
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
## 13.Просмотреть существующие ветки. 
## 14.Создать новую ветку. 
## 15.Переключиться на другую ветку. 
