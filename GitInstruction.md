# Инструкция по работе с git
 
##  Cоздание пректов

* `init` - Создание пустого Git-репозитория или повторная инициализация существующего репозитория.
Для получения более подробной информации см. [Git command](https://git-scm.com/docs/git-init).

* `clone` - Клонирование репозитория в новый каталог.
Для получения более подробной информации см. [Git сlone](https://git-scm.com/docs/git-clone).


## Основные команды

* `add` - Добавление содержимого файла в индекс. Или, другими словами, дать команду Git на отслеживание изменений в этом файле.
Для получения более подробной информации см. [add command](https://git-scm.com/docs/git-add). 

* `status` - Получение информации от git о его текущем состоянии.
Более подробная информация см. [status command](https://git-scm.com/docs/git-status).

* `git commit -m “message”` - Запись изменений в локальный репозиторий.
Для получения более подробной информации см. [commit command](https://git-scm.com/docs/git-commit). 

## Ветвления и слияния

* `checkout` - Переключение между ветвями. `git checkout master` - возвращение к актуальному состоянию и продолжение работы.
Для получения более подробной информации см. [checkout command](https://git-scm.com/docs/git-checkout). 

## Проверка и Сравнение

* `log` - Вывод на экран истории всех коммитов с их хеш-кодами.
Для получения более подробной информации см. [log command](https://git-scm.com/docs/git-log). 

* `diff` - Отображение различий между текущим файлом и закоммиченным файлом.  Для получения более подробной информации см. [diff command](https://git-scm.com/docs/git-diff).

## Совместное использование и обновление проектов

* `fetch` - Загрузка объектов и ссылок из другого хранилища.
Для получения более подробной информации см. [fetch command](https://git-scm.com/docs/git-fetch) 

* `pull` - Получение из другого репозитория или локальной ветки и интеграция с ним. Для получения более подробной информации см. [pull command](https://git-scm.com/docs/git-pull)

* `push` - Обновление удаленных репозиториев вместе со связанными с ними объектами. Для получения более подробной информации см. [push command](https://git-scm.com/docs/git-push)

## Что это и для чего нужна система контроля версий?

### Что такое система контроля версий?

### Для чего нужна система контроля версий

## Установка git и VSCode на ваш ПК.

### Установка VSCode на ваш ПК.

### Установка git на ваш ПК

#### Первая настройка git

## Создание и базовая работа с локальным репозиторием.

Для того чтобы создать свой локальный репозиторий, необходимо выбрать необходимую директорию через команду ``cd`` "адрес директории", после чего ввести ``git init``, после чего все другие команды git (такие как ``add``, ``commit``, ``branch`` и т.д.) начнут опозноваться и выполняться. После можно спокойно работать с имеющимися файлами в репозитории (вашей папке) и записывать их изменения через ``commit -m "Название сохранения"``, сохраняя их в ``log``.

### Что такое репозиторий и инструкция по созданию локальных репозиториев.

### Базовая работа с локальным репозиторием



## Ветки. Локальная работа с ветками в git.

### Что такое ветки и для чего они нужны при работе с системой контроля версий.

Ветки позволяют командам разработчиков без труда вести совместную работу с одной централизованной базой кода. Когда разработчик создает ветку, система контроля версий создает копию базы кода, актуальную на текущий момент времени. Изменения ветки не влияют на работу других разработчиков в команде. Это, конечно же, хорошо, потому что разработка функциональных возможностей сопряжена с постоянными изменениями, и если бы вся работа велась в главной ветке, процесс разработки погрузился бы в хаос. Но ветки не должны существовать в полной изоляции. Разработчики могут без труда запрашивать изменения у других разработчиков, чтобы вместе работать над функциональностью и не допускать слишком сильного отклонения их собственной ветки от главной.

### Базовая работа с ветками в git.

## Работа с удаленными репозиториями.

### Что такое удаленный репозиторий и для чего он нужен

### Базовая работа с удаленными репозиториями GitHub

## Совместная работа над проектом (fork, pull request)

### Как строится и для чего нужна совместная работа в системах контроля версий

### Инструкция по созданию pull request

## Книги и полезные ссылки по изучению git.

## Альтернативные системы контроля версий.
