# git
Мой первый репозиторий

Здесь будет моё резюме в HTML + CCS виде

1. Устанавливаем git локально на компьютер
2. Открывает **git bash** 
3. **git init**
4. Прописываем глобальные настройки, должны совпвдать с github
    **git config --global user.name** - Показывает имя пользователя
    **git config --global user.name 'new user'** — Изменяет имя пользователя
    **git config --global user.email — Показывает email** пользователя
    **git config --global user.email 'test@mail.ru'** — Изменяет email пользователя

5. Создать файл или файлы
6. **git status** - не обязательно
7. **git add .**
8. **git commit -m "Имя коммита"**
9. Зарегистрироваться на сайте github.com
10. Создать новый репозиторий
11. Добавить удалённый сервер
    **git branch -M main
    git remote add origin https://github.com/Antinio/test.git
    git push -u origin main**
12. Переключиться на ветку **main**
    **git checkout main**
13. **git push** - отправить изменения на удалённый сервер github.com
14. Забрать изменения с github
    **git pull**
