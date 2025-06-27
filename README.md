# How to use to different account of github for personal use and profession use

## Steps to push code for Secondary account:

## Generate ssh key

```bash
ssh-keygen -t ed25519 -C "email_address"
```

And then add to ssh agent. For more see GitHub guide.

### For first time

1. git init
2. git add .
3. git config user.name "your_username"
4. git config user.email "your_email"
5. git commit -m "message"

NOTE: Your host must be like "github.com-work" in ~/.ssh/config for secondary account then modify the origin url.

6. git remote add origin git@github.com-work:username/repo.git ( git remote add origin git@github.com-work:username/repo.git = for this case )
7. git push -u origin master

### After first

1. git add .
2. git commit -m "message"
3. git push
