# testing_Vadim_Ksendzov
GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
git branch Postman

- Jmeter
git branch Jmeter

- CheckLists
git branch CheckLists

- Bag Reports
git branch BagReports

- SQL
git branch SQL

- Charles
git branch Charles

- Mobile_testing
git branch Mobile_testing


2. Запушить все ветки на внешний репозиторий
git push --set-upstream origin Postman
git push --set-upstream origin Jmeter
git push --set-upstream origin CheckLists
git push --set-upstream origin BagReports
git push --set-upstream origin SQL
git push --set-upstream origin Charles
git push --set-upstream origin Mobile_testing

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
git checkout BagReports
cat >>bag_reports.txt
Bug id:
Title:
Severity:
Priority:
Environment:
Precondition:
STR:
AR:
ER:
Attachments:
ctrl+d

4. Запушить структуру багрепорта на внешний репозиторий
git add bag_reports.txt
git commit -m "add bag_reports.txt"
git push

5. Вмержить ветку Bag Reports в Main
git merge BagReports -m "merge BagReports"

6. Запушить main на внешний репозиторий.
git push

7. В ветке CheckLists набросать структуру чек листа.
git checkout CheckLists
cat >>check_list.txt
Number
Discription of checking
Expected result
Actual result
Comment

8. Запушить структуру на внешний репозиторий
git add check_list.txt
git commit -m "check_list.txt"
git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
- нажать кнопку "Pull requests"
- Compare & pull request - создаем запрос
- Creat pull requests - отправили запрос
- Merge pull request -> Confirm marge - мерджим

10. Синхронизировать Внешнюю и Локальную ветки Main
git fetch - проверить изменения
git pull - перетянуть все изменения
