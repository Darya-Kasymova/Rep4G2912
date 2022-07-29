# Руководство пользователя.
## Команды git:
* **git version** - проверка корректности установки программы, а также информация о ее версии;
* **git config** --global user.name "My Name"* - привязка программы к имени пользователя, работающего с документом;
* **git config** --global user.email myEmail@example.com - привязка информации о электронной почте пользователя,работающего с документом;
* **git init** - создание репозитория в выбранной папке (инициализация);
* **git status** - показывает текущий, актуальный статус репозитория;
* **git add** - добавление файлов для работы с ними из выбранной папки;
* **git commit** -m "Комментарий к комиту" - создание точки сохранения с комментарием;
* **git log** - просмотр журнала изменений;
* **git checkout** - переход к нужному коммиту;
* **clear** - очистка области в окне терминала.
* **git diff** - просмотр неподтвержденных изменений, внесенных после последнего коммита
* **q** - возврат к командной строке в терминале
## Правила оформления текста в Markdown
Заголовки
# H1
## H2
### H3

Начертание
Курсив обозначается одинарными *звездочками* или _подчеркиваниями_
Полужирный текст обозначаается двойными **звёздочками** или __подчеркиваниями__.
Для нужно начертания можно комбинировать **звёздочки и _подчеркивания_**.
Две тильды перечёркивают текст. ~~Перечеркнутый текст~~
## Добавление картинок
## Черновик для комментариев
Для конфликта при слиянии ветки chernovik добавлена строка.
 способ вставки картинки:
 *  ![Иконка Git](git_icon.jpg) "- иконка git"
 
 Предварительно скопировать картинку в папку с репозиторием, добавить ее в файл игнор.
 ## Черновик для комментариев