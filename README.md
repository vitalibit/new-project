# Кроки для створення нового публічного Git-репозиторію

## 1. Створіть в своєму середовищі новий каталог з назвою "new-project".
    mkdir new-project
## 2. Перейдіть до каталогу "new-project".
    cd new-project
## 3. Ініціалізуйте новий публічний Git-репозиторій всередині каталогу "new-project".
    git init
## 4. Створіть новий файл з назвою "README.md" і додайте до нього початковий текст.
    touch README.md
## 5. Підготуйте файл "README.md" до коміту.
    git add README.md
## 6. Закомітьте зміни у репозиторій з коміт повідомленням “init”.
    git commit -m "init"
## 7. Створіть нову гілку з назвою "development" і перейдіть до неї.
    git checkout -b development
## 8. Додайте інструкцію до файлу "README.md" і підготуйте їх до коміту. Закомітьте зміни у гілці "development" з повідомленням про коміт.
    git add README.md
    git commit -m "Add instructions to README"
## 9. Об'єднайте зміни з гілки "development" у гілку "main".
    git checkout main
    git merge development
## 10. Перевірте статус, переконайтеся, що все актуально.
    git status
## 11. Відправте зміни з локального на віддалений репозиторій
    git remote add origin <GitHub repo URL>
    git push -u origin main

