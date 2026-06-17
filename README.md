<!--
Это ШАБЛОН ОТЧЁТА. Заполните его своими данными по ходу работы.
Само задание со всеми шагами находится в файле TASK.md — его менять не нужно.
Заменяйте текст в [квадратных скобках] своими данными и удаляйте подсказки в <!-- ... -->.
-->

# Git Practice: [Фамилия Имя]

Учебный проект для закрепления Git, GitHub и VS Code: README.md, .gitignore,
коммиты, ветки, merge, fetch, pull и разрешение конфликтов.

> Инструкция к работе — в файле [TASK.md](TASK.md).

## Информация о студенте

| Поле             | Значение                                |
|------------------|-----------------------------------------|
| ФИО              | [Кононова Ника А ]                           |
| Группа           | [РПО1, 1 курс ]                       |
| Дисциплина       | Git и GitHub                            |
| Дата выполнения  | [17.06.2026]                            |
| Ссылка на GitHub | [https://github.com/nikaxzzl/kontrol_git_rpo]|

## Цель работы

Закрепить полный цикл работы с Git и GitHub через графический интерфейс VS Code.

## Описание выполненных этапов

1. Клонировала шаблон проекта из GitHub.
2. Проверила Git-репозиторий.
3. Создала файлы README.md, .gitignore, main.py, docs/notes.md.
4. Настроила .gitignore (.env, venv/, __pycache__/, *.log не попадают в Git).
5. Сделала несколько осмысленных коммитов через Source Control.
6. Опубликовала репозиторий на GitHub через Publish Branch.
7. Создала ветку feature/readme-update.
8. Внёсла изменения в ветке и сделала коммит.
9. Слила ветку в main через Merge.
10. Выполнила Fetch и Pull, увидела разницу.
11. Создала и разрешила конфликт в README.md.
12. Оформила README.md как отчёт со скриншотами.

## Использованные Git-действия

- Clone Repository
- Initialize Repository
- Stage Changes
- Commit
- Publish Branch
- Push / Sync Changes
- Fetch
- Pull
- Create Branch / Switch Branch
- Merge
- Resolve Conflict
- Git Graph

## Таблица Git-действий и их смысла

| Действие              | Где в VS Code                     | Смысл                                                   |
|-----------------------|-----------------------------------|---------------------------------------------------------|
| Clone Repository      | Command Palette → `Git: Clone`    | Копирует репозиторий с GitHub на компьютер              |
| Initialize Repository | Source Control                    | Создаёт локальный Git-репозиторий                       |
| Stage Changes         | Source Control, кнопка `+`         | Подготавливает файлы к коммиту                          |
| Commit                | Поле `Message` + кнопка `Commit`  | Сохраняет версию проекта в истории                      |
| Publish Branch        | Source Control                    | Публикует проект/ветку на GitHub                        |
| Push / Sync Changes   | Source Control                    | Отправляет и синхронизирует коммиты с GitHub            |
| Fetch                 | Source Control → `...` → `Fetch`  | Проверяет изменения на GitHub, не меняя локальные файлы |
| Pull                  | Source Control → `...` → `Pull`   | Загружает и применяет изменения с GitHub                |
| Create / Switch Branch| Панель снизу слева, Git Graph     | Создаёт и переключает ветки                             |
| Merge                 | Git Graph / Command Palette       | Объединяет изменения одной ветки с другой               |
| Resolve Conflict      | Редактор VS Code                  | Выбор или объединение конфликтующих изменений           |
| Git Graph             | Расширение Git Graph              | Показывает историю коммитов и веток                     |

## Разница между Fetch и Pull

Fetch показывает какие есть именения (новые коммиты). Не меняет раюочие файлы
Pull загружает изменения


## Конфликт и его решение

Я создала кофликт в файлке README.md
Я выбрала первоначальный вариант



## Скриншоты выполнения работы

### 1. Созданный проект в VS Code
![01](screenshots/01_repository_created.png)

### 2. Инициализированный репозиторий
![02](screenshots/02_git_initialized.png)

### 3. Первый коммит
![03](screenshots/03_first_commit.png)

### 4. Репозиторий на GitHub
![04](screenshots/04_github_repository.png)

### 5. Созданная ветка
![05](screenshots/05_branch_created.png)

### 6. Результат merge
![06](screenshots/06_merge_completed.png)

### 7. Выполнение Fetch / Pull
![07](screenshots/07_fetch_or_pull.png)

### 8. Итоговая история в Git Graph
![08](screenshots/08_final_git_graph.png)

## Вывод

В ходе работы, я научилась клонировать репозиторий, создавать файлы, вызываь и устранять ошибки, создавать ветки и сливать. Мне нравится работать в GitHub это интересно.

## Что я понял(а) про .gitignore

- `.gitignore` помогает не отправлять в GitHub временные и секретные файлы.
- Файл `.env` нельзя публиковать, потому что в нём могут быть токены и пароли.
- Логи `*.log` обычно не нужны в репозитории.
- Папки `venv/` и `.venv/` не добавляют в Git, потому что их можно создать заново.
- Перед коммитом нужно проверять Source Control.

Изменение, сделанное через GitHub
