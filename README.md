##Отчет по лабораторной работе №6 
##По курсу: Основы программирования
##Выполнил студент гр. 4916 А.В. Байбородин


###Ход работы:
На сайте GitHub сделал копию https://github.com/Kurtyanik/LR6/
![Копированный репозиторий](screenshots/screen1.jpg)
Настроил клиент, введя имя пользователя и email
![Персональные данные](screenshots/screen2.jpg)
С помощью команды _cd Desktop/ОП/LR6_ в консоли Git Bash перешёл в созданную папку LR6
Использовал команду _git init_ чтобы инициализировать гит в данной папке
![git init](screenshots/screen3.jpg)
Командой _git remote add origin_ связал папку с удалённым репозиторием и командой _git clone_ клонировал удаленный репозиторий на компьютер на сайте GitHub
![git remote add origin](screenshots/screen4.jpg)
Через интерфейс GitHub добавил новый файл _NewFile.txt_ в удалённый репозиторий и добавил его в ветку __master__
![Новый файл](screenshots/screen5.jpg)
![Новый файл](screenshots/screen6.jpg)
Используя команду _git pull origin master_ загрузил изменения из удалённого репозитория в локальный
![git pull](screenshots/screen7.jpg)
![git pull origin master](screenshots/screen8.jpg)
Командой _git log_ получил список коммитов
![git log](screenshots/screen9.jpg)
Используя _git show_ получил более подробную информацию по последнему изменению
![git show](screenshots/screen10.jpg)
Командой _git checkout -t branch1_ переключился ветку **branch1** и обратно на ветку **master**
![git checkout](screenshots/screen11.jpg)
При попытке выполнить слияние веток **master** и **branch1** с помощью команды _git merge branch1_ я получил ошибку
![Ошибка при слиянии](screenshots/screen12.jpg)
Вручную изменил содержание файла mergefile.txt, устранив ошибку слияния и выполнил коммит
![Изменил файл](screenshots/screen13.jpg)
Выполнил слияние веток **master** и **branch1** с помощью команды _git merge branch1_ и удалил ветку **branch1** командой _git branch -d branch1_
![Слияние и удаление](screenshots/screen14.jpg)
Занес всё в удалённый репозиторий командой _git push origin master_ 
![Push1](screenshots/screen15.jpg)
Добавил два новых файла
![File1,2](screenshots/screen16.jpg)
![File1,2 git log](screenshots/screen17.jpg)
Командой _git reset --hard HEAD~1_ выполнил откат последнего коммита, а именно добавления файла File2.txt и занес изменённую ветку в удаленный репозиторий
![hard](screenshots/screen18.jpg)
![push](screenshots/screen19.jpg)
Используя команду _git checkout -b report_ создал новую ветку **report**
![report](screenshots/screen20.jpg)
С помощью команды _git add ._ подготовил все новые файлы в папке LR6 к добавлению в удаленный репозиторий
![git add](screenshots/screen21.jpg)
Запушил файлы скриншотов в удалённый репозиторий
![git push](screenshots/screen22.jpg)
Оформил отчёт в файле README.md, используя блокнот
![Readme](screenshots/screen23.jpg)
Лог команд из папки **.git/logs**
![Logs](screenshots/screen24.jpg)
Финальный результат команды _git log_
![git logs](screenshots/screen25.jpg)
Все скриншоты лежат в папке **screenshots**