# **Памятка по работе с git.**

Что такое git ?
**Git** - это одна из реализаций распределенных систем контроля версий , имеющая как и локальные , так и удаленные репозитории . Является самой популярной реадизацией систем контроля версий в мире. 

# *Начало работы.*

1.Установка Git  
2.Создание репозитория- git init

# *Основные команды.*   
Проверка состояния файлов -git status
Добавление файлов в индекс - git add <filename> 
Фиксация изменения - git commit -m "описание изменения"   
Просмотр истории коммитов - git log  
Дерево коммитов - git log --graph
Выстроить дерево в одну линию - git log --oneline --graph 
Отмена последнего коммита - git revert HEAD 

# *Перемещение между сохранениями.*

Для того , чтобы перемещаться между коммитами , используется команда **git checkout "номер коммита".**


# *Ветвление.*   
Создание новой ветки - git branch <branchname>      
Переключение на другую ветку- git checkout<branchname>   
Удаление ветки - git branch -d <branchname>

# *Слияние веток.*
Для того чтобы добавить новую ветку в текущую , используется команда **git merge**

# *Лайфхак*
Для того чтобы сохранить изменения и сразу добавить коммит,одной командой ,  воспользуйтесь  **git commit -am"описание"**
Для того чтобы создать новую ветку и сразу перейти на нее , одной командой,  воспользуйтесь **git checkout -b**

