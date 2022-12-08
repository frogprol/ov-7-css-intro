# HTML, CSS, JS, Git intro

## Git 
 "доллар  в терминале в начале печатаь не нужно"
1. Chek version: 

    ```bash
    $ git --version
    $ ls -la
    $ rm -rf .git/
    ```

2.  Git init a new repository

`$ git init`

3. Index files

```bash
$ git status -  делаем всегда для проверки статуса 
$ git add . - добавляем в индексацию все файлики
$ git add index.html style.css - это примеры
```

4. Make a comit - делаем комит

```bash
$ git status
$ git commit -m "First commit"
```

5. Check commits

`$ git log`

6. Add remote rep

`$ git remote add origin https://github.com/frogprol/ov-7-css-intro.git` выбираем ссылку куда будет загружаться репозиторий с нашего компа на гитхаб

7. Send changes to the central repository

`$ git push origin master`
