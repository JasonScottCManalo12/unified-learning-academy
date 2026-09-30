Quick setup HTTPS — if you’ve done this kind of thing before
or	
https://github.com/JasonScottCManalo12/ula-final.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# ula-final" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/JasonScottCManalo12/ula-final.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/JasonScottCManalo12/ula-final.git
git branch -M main
git push -u origin main


Quick setup SSH  — if you’ve done this kind of thing before
or	
git@github.com:JasonScottCManalo12/ula-final.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# ula-final" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:JasonScottCManalo12/ula-final.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin git@github.com:JasonScottCManalo12/ula-final.git
git branch -M main
git push -u origin main



### Git & Github Issues

error: file too long
    solution: 
        git config --system core.longpaths true
        https://stackoverflow.com/questions/22575662/filename-too-long-in-git-for-windows

error: no access rights
    solution: 
        generate ssh key
        connect generated ssh key to github account
        publish repository

eror: repo 404
    solution: 
        git commit --allow-empty -m "Trigger rebuild"
