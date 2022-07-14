Чтобы увидеть список всех имеющихся веток используем:

>git branch 

Чтобы создать новую ветку используем :
> git branch branch_name  - создается ветка с именем branch_name

Чтобы удалить ветку, используем :
> git branch -d branch_name - удаляем ветку с именем branch_name с проверкой на merge
> git branch -D branch_name - удаляем ветку с именем branch_name без проверки на merge

Чтобы перейти к другой ветке используем:
> git checkout branch_name  - переходим к ветке с именем branch_name

Чтобы создать изменение и его коммит, используем:
> git commit -a -m"message"

Чтобы создать ветку и сразу перейти в нее используем:
> git checkout -b branch_name  - создается ветка с именем branch_name и происходит переход в нее