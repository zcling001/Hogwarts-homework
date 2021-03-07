### 测试上传到githubhttps://github.com/zcling001/Hogwarts-homework.git

echo "# Hogwarts-homework" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/zcling001/Hogwarts-homework.git
git push -u origin main