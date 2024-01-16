[< к содержанию](readme.md)

##  Основные команды для ветвей:

**git branch (Branch name)**.	
- Команда, которая создает новую ветку в репозитории.

```bach=
git branch Vitaly 
``` 
**git checkout (Branch name)**
- Команда, которая переключает вас на определенную ветку.

```bach=
git checkout Vitaly 
``` 
**git merge (Branch name)**
- Поглощение. Вносит коммиты из другой ветки в текущую.
```bach=
git merge Vitaly1
``` 
**git rebase (Branch name)**
- Перебазирование. В этом случае коммиты вашей ветки накладываются поверх текущего состояния указанной ветки.
```bach=
git rebase Vitaly1
``` 
**git checkout -b (Branch name)**
- Создаёт новую ветку и переключает вас на неё.
```bach=
git checkout -b Vitaly2
``` 
