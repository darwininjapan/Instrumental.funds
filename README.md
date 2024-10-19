# Instrumental.funds
Инструментальные средства разработки

git init

echo "# Проект" > README.md
git add README.md
git commit -m "Добавлен README.md"

git checkout -b feature/add-feature

echo "Новая функция" > feature.txt
git add feature.txt
git commit -m "Добавлена новая функция"

git checkout main

git merge feature/add-feature

git log --oneline
