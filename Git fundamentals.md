# Git Fundamentals

> some comands used in terminal

- git init  
  To Initialize empty Git repository
- git add .  
  Command used for staged changes
- git reset  
  To unstage the changes
- git commit -m "Type the msg here"  
  This command is to commit the changes with a message
- git status  
  To know the status
- git log  
  To know what are all the commits made till now
  - log filter
    - --author -> filter by author
    - -2 -> last commit
  - -p -> patch
  - -S -> pick-axe - search
  - git log `-S<word>` -p
    - `/<word>` - highlight search
    - `<space>` - page down
    - `n` - next match
    - `N` - prev match

> Git VS Github

Git is a software , whereas github is a place to store the documents or files.  
Git is a Distributed System

- Git has 3 stages:

  1. Working
  2. Staging
  3. Commit

- When u should make a commit ?

  1. When there is a logical change
  2. Commit should be done for small changes
  3. Should commit multiple times a day
  4. Always commit when ur code is working

> VIM

- Verb + Number + Movement
