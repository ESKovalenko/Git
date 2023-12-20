# Git
## Homework

1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

`git branch Postman`

`git branch Jmeter`

`git branch Check_list`

`git branch Bug_report`

`git branch SQL`

`git branch Charles`

`git branch Mobile_testing`

2. Запушить все ветки на внешний репозиторий

`git commit -a -m "branches"`

`git push origin --all`


3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

`git checkout bug_report`

`cat > bug_report.txt`

 1. Title
 2. Description
 3. StepsToReproduce
 4. ExpectedResult 
 5. ActualResult
 6. Severity
 7. Priority
 8. Environment
 9. Attachments

4. Запушить структуру багрепорта на внешний репозиторий

`git add .`

`git commit -m “bug_report.txt”`

`git push`

5. Вмержить ветку Bag Reports в Main
   
`git checkout main`

`git branch`

`git merge bug_report`

6. Запушить main на внешний репозиторий.
   
`git add .`

`got commit -m “branch_main”`

`git push`

7. В ветке CheckLists набросать структуру чек листа.

`git checkout Check_list`

`cat > Check_list`

 1. ID
 2. Title
 3. Inputs
 4. Expected result
 5. Actual result
 6. Status
 7. Bug

8. Запушить структуру на внешний репозиторий
   
`git add .`

`git commit -m “Check_list”`

`git push`

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
  
`Compare & pull request`

10. Синхронизировать Внешнюю и Локальную ветки Main

`git pull`
