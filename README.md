# Урок 1. Работа с удалёнными репозиториями

## Classwork

### Теория:

#### Команды подключения к удалённым репозиториям

git init
git clone path
git remote add origin path
git push -u origin master

#### Команды синхронизации веток

git push origin branch
git remote show origin
git fetch
git log remote_branch ^local_branch
git pull origin branch

#### Команды управления связями с удалёнными репозиториями

git remote add origin path
git remote show origin
git remote -v
git remote remove origin
git remote set-url origin new_path
git remote set-url –-fetch origin new_path
git remote set-url –-push origin new_path
git remote set-url --add –-push origin new_path
git fetch --all