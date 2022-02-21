# HOMEWORK GIT. JSON
JSON
1. Создать внешний репозиторий c названием JSON.

 - Заходим на github.com  в свой аккаунт. 
 - Переходим на вкладку "Repositories" и создаем новый репозиторий c названием JSON. 

2. Клонировать репозиторий JSON на локальный компьютер.

 - Нажимаем вкладку "Code" и копируем ссылку. 
 - Переходим в  = git bash 
 - В разделе создаем папку =  mkdir 2homework
 - Заходим в папку = cd 2homework
 - git clone ( вставляем то что скуопировали) https://github.com/Pitsenko/TXT.git 

3. Внутри локального JSON создать файл “new.json”.

 - touch new.json

4. Добавить файл под гит.

 - git add new.json

5. Закоммитить файл.

 - git commit -m "Add new.json file"

6. Отправить файл на внешний GitHub репозиторий.

 - git push 

7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

 - vim new.json (Вносим данные)
 - ESQ -> :WQ -> Enter 

8. Отправить изменения на внешний репозиторий.

 - git add new.json
 - git commit -am "change file. Added comments in the file"
 - git push 

9. Создать файл preferences.json

 - touch preferences.json

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате json.

 - vim preferences.json (Вносим данные)
 - ESQ -> :WQ -> Enter

11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате json.

 - vim preferences.json (Вносим данные)
 - ESQ -> :WQ -> Enter

12. Сделать коммит в одну строку. 

 - git add . | git commit -m "Add 2 files with comment"
 - git push

13. На веб интерфейсе создать файл bug_report.json

 - Заходим на свою страницу в github.com -> Repositories -> JSON -> Add file -> Create new file -> Имя файла bug_report.json

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 - Edit repository details -> save changes

15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате json.

 - Нажимаем на bug_report.json ->  edit this file ->  Пишем  баг репорт. 

16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 - Edit repository details -> save changes

17. Синхронизировать внешний и локальный репозиторий JSON

 - переходим в git bash
 - git pull 
 
