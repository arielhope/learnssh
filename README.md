# How to use to different account of github for personal use and profession use

## Steps to push code for secondary account:

### For first time

1. git init
2. git config user.name "your_username"
3. git config user.email "your_email"
4. git add .
5. git commit -m "message"

NOTE: origin url must modify from original.

6. git add origin git@github-yourSSHhost:username/repo.git ( git remote add origin git@github.com-work:username/repo.git )
7. git push origin main

### After first

1. git add .
2. git commit -m "message"
3. git push origin main
