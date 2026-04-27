# 1. Git Basic Concepts

## 1.1. Differenciating concepts

- Git:
  
  - A tool to track changes in repositories
  
  - Exists locally

- GitHub
  
  - A management environment /navigator for repositories tracking timeline
  
  - Uses git in the backgroud
  
  - Exists

## 1.2. How to start basic tracking with `git`

### Start git in project (repository)

Only once in the repository, no need to reactivate in sub-folders

```bash
user$ git init
```

### Set git configurations

Check if `git` has your information in the `config` file

```bash
user$ git config --global --list
```

Add or change your information

```bash
user$ git config --global user.name "Your Name"
user$ git config --global user.email "you_email@domain.com"
```

### Commit

Different from 'save'! Whenever you want to keep the current version, send it to `.git` folder.

**Files need to be saved before commit!**

```bash
user$ git add file.md
user$ git commit -m "[meaningful message]"
```

#### Meaningful message

For you and your collaborators to remember changes.

- **Why** was changed

- **How** this addresses previous issues

- **Effects** due to changes

- **Limitations** of the change

#### 
