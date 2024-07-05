# 通过github_pat个人访问令牌拉取GitHub项目

## 两种类型

1. 如果所拉取的项目所有者是你自己，则直接使用你的用户名作为用户名；
2. 假如项目所有者不是你，你也可以使用所有者的用户名，或者使用你的GitHub用户名。

## 使用格式

```bash
git clone https://{用户名}:{令牌字符串，比如：github_pat_xxx}@github.com/{带.git后缀的文件clone路径}
```

## 带.git后缀的文件clone路径哪里获取

1. 直接询问所有者；
2. 项目主页；
3. 直接在项目地址后+“.git”。

![1720150122841](images/0001-通过github_pat个人访问令牌拉取GitHub项目/1720150122841.png)

![1720150566602](images/0001-通过github_pat个人访问令牌拉取GitHub项目/1720150566602.png)
