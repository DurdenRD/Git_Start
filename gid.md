

### Представление

**git config --global user.name** "<ваше_имя>" - имя
**git config --global user.email** "<адрес_почты@email.com>" - почта

### Репозиторий

**git init** - создание репозитория, скрытый файл
**git log** - журнал изменений.
**git log --oneline** - сокащенный лог, по одной строке 
**git status** - статус происходящего.

### Коммит

**git add** <имя файла> - добавление в очередь отслеживания
**git add .** -добавить все файлы 
**git rm** <имя файла> - удаляет из очереди
**git commit -m** "комментарий" - добавление коментария

### Просмотр состояния репозитория

**git log** - журнал изменений, каких-то событий, которые у нас хранятся.
**git status** -  что Git думает о нашей папке и её содержимом, а также статус происходящего.
**git diff** - отличие текущего файл от сохраненного или коммита.


### Работа с ветками

**git branch <имя ветки>** - создании новой ветки 
**git branch -d <имя ветки>>** - удаление ветки
**git branch -m <имя ветки>** - переименовать ветку
**git checkout**  - команда перехода.
 
_Можем указать либо название целиком, либо первые четыре символа, что и позволк_

**Git checkout -b <имя ветки>** - создание и переход в новую ветку
**Git merge <имя ветки>** - слияние ветки с текущей.
**git checkout master** - позволяет вернутся в исходный файл
Master.

### GitHub

**git remote add origin https://github.com/DurdenRD/Git_Start.git** - адресс репозитория на GitHub
**git branch -M main** - имя главной ветки
**git push -u origin main** - отправить главную ветку в репозиторий GitHub

**git push** - далее,перенести изменения файла с пк в GitHub
**git pull** - перенести изменения файла с GitHub на пк
**git clone** - клонировать репозиторий с GitHub на пк

### Как сделать pull request
1. Fork - вставляем репозитория в description
2. Создать папку для проекта
3.  **Git clone** <адрес> - клонируем проект
3. **cd** <выбрать папку> - прокладываем путь
4. **git log** можем просмотреть изменения
5. Создаем отдельную ветку для редактирования
6. **git push** - отправляем свою версию на GitHub
7. На сайте GitHub нажимаем кнопку pull request
 


        



### Markdown

## Выделения текста

либо "*"
либо "_"

Можно совмещать например *курсивом и при этом __полужирным__ шрифтом*.
 
 *курсив текст*
**жирный текст**
***курсив+жирный***

## Списки

Точки:

* Элемент 1
* Элемент 2
* Элемент 3

Список:

1. Первый пункт
2. Второй пункт
3. Третий пункт
