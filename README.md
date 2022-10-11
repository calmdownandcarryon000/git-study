# git-study

下载 GitHub 官方的客户端：https://cli.github.com/

第一次使用时，执行下面的命令登录 GitHub 账号：

```shell
gh auth login
```

## Clone Repo

```shell
gh repo clone calmdownandcarryon000/git-study
cd git-study
gh repo fork # will create upstream and origin
```

## Commit and push code

1. Create a branch

```shell
git checkout -b feature-xx
```

2. Commit and push

```shell
git add . # or git add some-dir
git commit -m 'I did something' # m means message
git push -u origin feature-xx
```

3. Create PR
```shell
gh pr create
```

## Check status

```shell
git status
```
