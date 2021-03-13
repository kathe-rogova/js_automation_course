# Git Base Level

1. Авторизуемся на сайте `github.com`
2. Создаём новый репозиторий `js_automation_course`
3. Клонируем созданный репозиторий на локальную машину

```bash
git clone https://github.com/kathe-rogova/js_automation_course.git
```

4. Создаём ветку `develop`

```bash
git checkout -b develop
```

5. Создаём и заполняем `README.md` для внесения изменений в `develop-branch`.
6. Создаём коммит с внесёнными изменениями.

```bash
git add .
git commit -m 'readme file has been created'
git push origin develop
```

7. Идём на github.com и создаём `pull request` в `master-branch`