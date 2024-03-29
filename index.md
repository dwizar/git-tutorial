# Основные команды GIT

## Содержание
* Инициализация нового репозитория
* Добавление файла в коммит
* Выполнение коммита изменений
* Журнал коммитов
* Временно переключиться на другой коммит
* Больше информации
* Котик

## Инициализация нового репозитория

Войдите в папку с файлами проекта и введите команду
```
git init
```

## Инициализация нового репозитория

Войдите в папку с файлами проекта и введите команду
```
git init
```

## Журнал коммитов
Что просмостреть журнал коммитов необходимо выполнить следующую команду

```
git log
```

## Временно переключиться на другой коммит

Чтобы временно переключиться на другой коммит необходимо использовать следующую команду с параметром, содержащим хеш коммита (или первые четыре символа)

```
git checkout 1a66
```

## Больше информации

Больше информации об использовании Git можной найти по [ссылке](https://git-scm.com/docs).

## Котик

Это картинка с котиком

![Текст с описанием картинки](/CatPicture.jpeg)

## Посмотреть разницу между коммитами или ветками

Команда git diff используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между вашей рабочей директорией и индексом (собственно git diff), разница между индексом и последним коммитом (git diff --staged), или между любыми двумя коммитами (git diff master branchB).

```
git diff
```
## Создать отдельную ветку изменений

Команда git branch — это своего рода “менеджер веток”. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их. Чтобы создать отдельную ветку, используйте команду

```
git branch _branch_name_
```

## Загрузить изменения из удаленного репозитория

Команда git fetch связывается с удалённым репозиторием и забирает из него все изменения, которых у вас пока нет и сохраняет их локально.. Чтобызагрузить изменения из удаленного репозитория, используйте команду

```
git fetch _fetch_address_
```
## Загрузить изменения из удаленного репозитория и любединить с локальным репозиторием

Команда git pull работает как комбинация команд git fetch и git merge, т.е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой. Чтобы загрузить и слить изменения, используйте команду

```
git pull _repo_address_
```
