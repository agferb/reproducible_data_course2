# 1. Git Basic Concepts

## 1.1. Differenciating concepts

- Git:
  
  - A tool to track changes in repositories
  
  - Exists locally

- GitHub
  
  - A management environment /navigator for repositories tracking timeline
  
  - Uses git in the backgroud
  
  - Exists

## 1.2. How to start  `git` in repository

#### Init git in project (repository)

Only once in the repository, no need to reactivate in sub-folders

```bash
git init
```

#### Set git configurations

Check if `git` has your information in the `config` file

```bash
git config --global --list
```

Add or change your information

```bash
git config --global user.name "Your Name"
git config --global user.email "you_email@domain.com"
```

## 1.3. How to add commits

Different from 'save'! Whenever you want to keep the current version, send it to `.git` folder.

**Files need to be saved before commit!**

```bash
git add file.md
git commit -m "[meaningful message]"
```

#### Meaningful message

For you and your collaborators to remember tracks

- **Why** was changed

- **How** this addresses previous issues

- **Effects** due to changes

- **Limitations** of the change

#### More detailed message

```bash
git commit
```

Will open text editor to write a commit message.

#### Change to other message editors

```bash
git config --global core.editor "nano"        # Nano
git config --global core.editor "code --wait" # VSCode
```

## 1.4. Staging area

Folder to keep files to be tracked before adding a global commit message.
