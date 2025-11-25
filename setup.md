# Git Setup & Configuration

## Install Git
Download from: https://git-scm.com/

Check version:
```bash
git --version
```

## Configure Git (mandatory)
```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

View configs:
```bash
git config --list
git config --global --list
```

Remove a config:
```bash
git config --global --unset user.name
```

## Shell Tools
| Tool | What it is | Why used |
|------|------------|----------|
| Command Prompt | Old shell | Legacy tools |
| PowerShell | Modern Windows shell | Automation |
| Windows Terminal | A hub to open PowerShell/CMD | Best dev experience |

Basic commands:
```bash
pwd
ls
cd folder
mkdir name
rm -r folder
```
