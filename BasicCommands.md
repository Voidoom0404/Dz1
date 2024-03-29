[< к содержанию](readme.md)

## Основные команды Git:

| Команды |   Описание|   Пример
| :----: | :---: | :-------: |
|git add <file>  | Добавляет определенный файл в промежуточную область.   |
| git add –all     | Добавляет все измененные и новые файлы в промежуточную область.  | ---       |
| git status   |Показывает текущее состояние вашего репозитория, включая отслеживаемые и неотслеживаемые файлы, измененные файлы и информацию о филиале.       | ---        |
| git status –ignored     | Отображает игнорируемые файлы в дополнение к обычному выводу состояния.  |   ---     |
| git diff     | Показывает изменения между рабочим каталогом и промежуточной областью (индексом).      | ---        |
| git commit  | Создает новый коммит с изменениями в промежуточной области и открывает текстовый редактор по умолчанию для добавления сообщения о коммите.   | ---       |
| git notes add     |Создает новую заметку и связывает ее с объектом (фиксацией, тегом и т.д.).       | ---     |
| git restore <file>     | Восстанавливает файл в рабочем каталоге до состояния, в котором он находился при последней фиксации.  |git restore Vitaly       |
| git reset <commit>    | Перемещает указатель ветви на указанный коммит, сбрасывая промежуточную область и рабочий каталог, чтобы они соответствовали указанному коммиту.      | ---       |
| git rm <file>   | Удаляет файл как из рабочего каталога, так и из репозитория, инициируя удаление.  | git rm Vitaly        |
| git mv    | Перемещает или переименовывает файл или каталог в вашем репозитории Git.      | ---       |