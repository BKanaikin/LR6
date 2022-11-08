# LR6
Лабораторная работа №6

**Цель работы:** изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

**Ход работы.**

Копия в личное хранилище (Fork).
![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen1.png)

Настройка имени пользователя и email'a при помощи команд git config --global user.name и git config --global user.email.
![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen2.png)

Клонирование удаленного репозитория на компьютер при помощи команды git clone.
![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen3.png)

Добавление файла через интерфейс GitHub и подтягивание изменений в локальный репозиторий с помощью команды git pull. Далее работу локально будем продолжать в VSCode.
![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen4.png)

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen5.png)

Получение истории операций при помощи команды git log.
![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen6.png)

Просмотр последних изменений командой git reflog.
![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen7.png)

Создаем новую ветку командой и сразу переходим в нее при помощи команды git checkout -b branch-name. Далее изменяем новый файл и коммитим командами git add ., git commit -m "text".
![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen8.png)

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen9.png)

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen10.png)

Переходим в ветку мастер командой get checkout и выполняем слияние с веткой branch1 командой git merge.

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen11.png)

Удаляем побочную побочную ветку командой git branch -d.

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen12.png)

Изменим файл и закоммитим изменения. 

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen13.png)

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen14.png)

Затем снова изменим файл и сделаем коммит.

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen15.png)

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen16.png)

Сделаем откат коммита командой git reset --hard HEAD~1.

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen17.png)

Создадим новую ветку для отчета.

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen18.png)

Запушим изменения на удаленный репозиторий командой git push --set-upstream.

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen19.png) 

Лог команд.

![](https://github.com/BKanaikin/LR6/blob/report/screenshots/screen20.png)

**Вывод:** я изучил базовые возможности системы управления версиями, получил опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.