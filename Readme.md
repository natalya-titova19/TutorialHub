# инстукция по работе с git и удаленными репозиториями 

## что такое git ?
Git это одна из реализаций распределенных систем контроля версий , имеющая как локальные , так и удаленные репозитории . Является самой популярной реализацией систем контроля в мире. 
## подготовка репозиториев 
Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий 
## создание коммитов 
Для того, чтобы создать коммит необходимо выполнить команду  *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** ,к коммиту обязательно писать пояснение 
### git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*
## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*


## Журнал изменений 



## Ветки в Git


### Создание ветки 
Для того , чтобы создать ветку , используем команду *git branch* . Делается это следующим образом в папке с репозиторием : *git branch <название новой ветки>*

## Слияние веток 
Для того , чтобы добавить ветку в текущую ветку используется команда "git merge <name branch>*

## Удаление веток 
Для удаления ветки ввести команду "git branch -d 'name branch'" .

## Создание конфликтов 
Конфликты создаются при разном описании одного и того же действия на разных ветках при их слиянии .Конфликт можно решить предложенными командами или в ручную через команду <both change>.

## Создание конфликтов 
Создание конфликта это одна и таже запись либо разная полача одной и той же информации на разных ветках .
бесконечно тупящие студенты тратят время всех впустую , в итоге запутывают еще больше остальных . Вывод делаешь все на автомате за преподавателем , ничего не понимаешь и это раздражает .

Для описания проектов на GitHub используется Readme.md, который пишется на языке разметки markdown. Что и как поддерживается расписано ниже. Так же существует еще один формат - reStructuredText,описание которого внесено в отдельный файл Readme.rst 

проверяем , что будет если внесем изменения и запушим их с не основной своей ветки .



# Работа с удаленными репозиториями 

## Что такое удаленный репозиторий 

Удаленный репозиторий представляет собой версии наших проектов , сохраненные в интеренете. Например : сервис GitHub.


## Для чего используется удаленный репозиторий 

Удаленный репозиторий нужен для коллективной работы над проектом , таким образом каждый из участников может вносить изменения , отправлять из в удаленный репозитории , чтобы остальные могли ознакомиться с внесенными изменениями 

## Какие команды используются при работе с удаленным репозиторием 

1. Git pull - выкачиваем данные из удаленного репозитория в локальный 

2. Git push - отправляем внесенные изменения из локального в удаленный репозиторий 
