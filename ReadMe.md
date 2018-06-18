Hello Git

===============

Study it again and again

Add \r \n

update second time

git merge --no-ff

update at corperation

add config to .ssh/config file

can resolve the multi machine commit problem


config like this:

#Default Github
Host github.com

    HostName github.com

    User git

    IdentityFile ~/.ssh/id_rsa_github

modify default config

git config --system # 系统中对所有用户都普遍适用的配置

git config --global  # 设定当前用户的git配置

git config xxx   # 设定当前项目的git配置


#追加到上一次提交
git ci --amend     #是否修改上次 comment :wq退出编辑，push到远程即可
