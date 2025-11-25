# SSH Setup for GitHub

## Why SSH?
Secure login without typing password.

## Steps
```bash
cd ~
ls -a
mkdir .ssh
cd .ssh
ssh-keygen -o -t rsa -C "email@example.com"
ls
```

Open public key:
```bash
code id_rsa.pub
```

Copy → GitHub → Settings → SSH Keys
