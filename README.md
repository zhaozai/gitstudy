# Hello Git

===============

Study git again and again

Add \r \n

### Commit without using fast-forward mode will have a clean tree insight

``` 
git merge --no-ff
```

update at cooperation

### Multiply machine commit to multi repository problem
add config to .ssh/config file
content like bellow :

```
#Default Github
Host github.com
    HostName github.com
    User git
    IdentityFile ~/.ssh/id_rsa_github
```

### Configuration working scope

```
git config --system # 系统中对所有用户都普遍适用的配置

git config --global  # 设定当前用户的git配置

git config xxx   # 设定当前项目的git配置
```

### 追加到上一次提交

```
git ci --amend     #是否修改上次 comment :wq退出编辑，push到远程即可
```

### 跳过暂存区提交

```
git ci -a -m "skip cached area commit"
```

