# JSON

 4. Создать внешний репозиторий c названием JSON.
 5. Клонировать репозиторий JSON на локальный компьютер. - git clone https://github.com/NyraRubka/JSON.git
 6. Внутри локального JSON создать файл “new.json”. -  cat > new.json
 7. Добавить файл под гит. - git add new.json
 8. Закоммитить файл. - git commit -m "ver1"
 9. Отправить файл на внешний GitHub репозиторий. - git push
 10. Отредактировать содержание файла “new.json” - vim new.json
написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
{
 "Name":"Ann",
 "Surname":"Yerchenko",
 "old":"27",
 "pet":"0",
 "salary":"1000"
 }
 11. Отправить изменения на внешний репозиторий. git commit -am "add info", git push
 12. Создать файл preferences.json - vim preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
{
        "film":"adam",
        "serial":"eva",
        "food":"fish",
        "time of the year":"summer",
        "contry":"Canada"
}

 14. Создать файл sklls.json - vim skill.json
добавить информацию о скиллах которые будут изучены на курсе в формате JSON
{
        "JS":"medium",
        "Terminal":"medium",
        "JSON":"medium",
        "Postman":"medium"
}

 15. Отправить сразу 2 файла на внешний репозиторий. - git add ., git commit -m "new file", git push
 16. На веб интерфейсе создать файл bug_report.json.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
{
"ID":"",
"Summary":"",
"Description":"",
"Steps To Reproduce":"",
"Actual Result":"",
"Expected Result":"",
"Attachments":"",
"Priority":"",
"Severity":"",
"Status":"",
"Component/Environment":"",
"Fix Version":"",
"Assignee":""

}
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON - git pull
