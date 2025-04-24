# How to use to different account of github for personal use and profession use

## Steps to push code for Secondary account:

### For first time

1. git init
2. git add .
3. git commit -m "message"

NOTE: Your host must be like "github.com-work" in ~/.ssh/config for secondary account then do modify the origin url.

6. git remote add origin git@github.com-work:username/repo.git ( git remote add origin git@github.com-work:username/repo.git = for this case )
7. git push -u origin main

### After first

1. git add .
2. git commit -m "message"
3. git push
