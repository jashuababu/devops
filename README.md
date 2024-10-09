Creating the new repository on the comment line

echo "# sample" >> README.md
git init
git add README.md
git commit -m "first commit"
branch -M main
remote add origin hhtps://github.com/pknowledge/sample.git
push -u origin main
