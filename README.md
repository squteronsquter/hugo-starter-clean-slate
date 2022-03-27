# How to steps

```
cd ~/Sites 

mkdir hugo_projects

hugo new site placakijakptaki

cd placakijakptaki

git init

git add .

git status

git commit -m "initial commit"

git branch -M main

git remote add origin https://github.com/squteronsquter/hugo-starter-clean-slate.git

git push -u origin main

hugo mod init  github.com/squteronsquter/hugo-starter-clean-slate

# adding Ananke theme as hugo mod

# edit config.toml

baseURL = 'https://plecakijakptaki.pl/'
languageCode = 'pl-pl'
title = 'Plecaki jak ptaki'
theme = ["github.com/theNewDynamic/gohugo-theme-ananke"]

# add Ananke

git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

# build or run server in dev mode

hugo

hugo server

```
