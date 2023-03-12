```git
git config user.name "Aman"
```

```git
git config user.email "aman.proj.rel@gmail.com"
```

```git
touch .gitignore
```

[Source of below command](https://stackoverflow.com/questions/61743148/where-is-git-reflog-expire-configuration-stored)

```git
git config gc.reflogExpire never
```

<!-- git config --global gc.reflogExpire never -->

```git
git config alias.last 'log -1 HEAD --stat'
```

```git
git config alias.search '!git rev-list --all | xargs git grep -F'
```

```git
git config alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --"
```

```git
git lg
```

<!-- [May it can help](https://stackoverflow.com/questions/5834014/lf-will-be-replaced-by-crlf-in-git-what-is-that-and-is-it-important) -->
