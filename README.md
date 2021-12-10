# Guide-to-using-Git

#...or create a new repository on the command line
echo "# 08-finished" >> README.md
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/user/repo.git
git push -u origin main
```

#...or push an existing repository from the command line
```
git remote add origin https://github.com/user/repo.git
git branch -M main
git push -u origin main
```

# Push the code to repository after change it
```
git add .
git commit -m "reason for change"
git push origin main

<image src="https://user-images.githubusercontent.com/54015766/145498996-df182e66-d39c-4939-8159-47f47a8554c6.png" />
![image](https://user-images.githubusercontent.com/54015766/145498996-df182e66-d39c-4939-8159-47f47a8554c6.png)
