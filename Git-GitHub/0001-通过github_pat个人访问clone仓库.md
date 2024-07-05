# 0001-通过github_pat个人访问clone仓库

## 前提是获取项目的token

1. github_pat token 是GitHub推出的用于取代用户名与密码的加密秘钥，是一种私钥，可以理解为密码。
2. token不是真正的秘钥，可以理解为对秘钥的加密，或者对存放秘钥获取方式的加密。
3. 因此，要通过token访问GitHub项目，除了指导token字符串，还需要知道项目的地址+用户名。

## 通过git clone命令克隆项目

```bash
git clone https://{用户名}:your-token@github.com/{项目开发者名或地址}/{仓库名称}.git
```

## 注意事项

1. 使用这种方式克隆项目，容易造成最新版的VS Code+最新版的Git结合使用的时候出现下面的提示：
   ![1720170236576](images/0001-通过github_pat个人访问clone仓库/1720170236576.png)
2. 出现上面提示的解决办法是：重新安装 VS Code.
3. 因此，不建议使用github_pat的方式分享项目。

---
