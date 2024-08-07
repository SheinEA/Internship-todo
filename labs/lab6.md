### Тема
Решение Todo, библиотеки классов

### Время на выполнение 
10 дней

### Задание
1. Перейти в корень репозитория на локальной машине и создать ветку от main с наименованием по шаблону <наименование_работы>_<номер_студенческого_билета>, например, lab6_325689.
2. Перейти в свой каталог студента и создать новое пустое решение (solution) с именем Student.
3. Добавить в решение ранее созданные проекты Student.ConsoleTodo и Student.WindowsTodo.
4. Создать в решении новый проект типа Class Library с наименованием Student.Todo.
5. Подключить проект Student.Todo к проектам Student.ConsoleTodo и Student.WindowsTodo как ссылку (References).
6. Провести рефакторинг проектов Student.ConsoleTodo и Student.WindowsTodo, вынести классы по работе со списком задач в проект
Student.Todo. Классы не должен быть зависимым от типа приложения, в классах должна быть реализована только логика работы с задачами.
7. Выполнить синхронизацию изменений локального репозитория в удаленный.
8. Создать pull request в ветку main. Создание pull request выполняется из интерфейса вашей системы контроля версий кода (например, GitHub, GitLab).
9. По завершению предоставить ссылку на pull request.
10. Пройти code review со стороны вашего куратора стажировки и исправить все замечания к коду программы.
11. После получения согласования вашего pull request, выполнить его сливание в ветку main c использованием параметра squash (для исключения промежуточных commits). Сливание pull request выполняется из интерфейса вашей системы контроля версий кода (например, GitHub, GitLab).
12. По завершению предоставить ссылку на репозиторий.

### Критерии приема работы
1. Пройти по предоставленной ссылки и провести code review. 
2. Получить удаленный репозиторий по предоставленной ссылке. Проверить работоспособность приложениий на нескольких контрольных примерах в том числе добавить более 2х задач.

### Ссылки для самостоятельного изучения:
1. https://metanit.com/sharp/tutorial/3.46.php
2. https://learn.microsoft.com/ru-ru/dotnet/core/tutorials/library-with-visual-studio?pivots=dotnet-7-0
3. https://web-creator.ru/articles/refactoring