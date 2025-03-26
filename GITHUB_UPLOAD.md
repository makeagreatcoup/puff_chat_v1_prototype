# GitHub仓库上传指南

本文档提供如何将当前健身饮食App项目上传到GitHub的详细步骤。

## 前置条件

1. 已拥有GitHub账号
2. 已安装Git客户端
3. 已完成本地仓库的初始化和提交（已完成）

## 步骤一：在GitHub创建新仓库

1. 登录GitHub账号：https://github.com/login
2. 点击右上角"+"图标，选择"New repository"
3. 填写仓库信息：
   - Repository name: `fitness-nutrition-app`（或您喜欢的名称）
   - Description: 健身饮食App原型，基于现代UI设计，包含多个功能模块
   - 选择"Public"或"Private"（根据个人需求）
   - 不要勾选"Initialize this repository with a README"
4. 点击"Create repository"

## 步骤二：连接本地仓库与GitHub仓库

在命令行中执行以下命令（将URL替换为您自己的仓库URL）：

```bash
# 添加远程仓库
git remote add origin https://github.com/您的用户名/fitness-nutrition-app.git

# 推送代码到GitHub
git push -u origin master
```

执行过程中，系统可能会要求您输入GitHub用户名和密码（或令牌）。

## 步骤三：验证上传结果

1. 打开浏览器，访问您的GitHub仓库页面
2. 确认所有文件已成功上传
3. README.md文件将自动显示在仓库主页上

## 后续更新

当您对代码进行修改后，可以使用以下命令将更新推送到GitHub：

```bash
# 添加修改的文件
git add .

# 提交修改
git commit -m "更新说明"

# 推送到GitHub
git push
```

## 常见问题解决

### 1. 认证失败

如果使用密码认证失败，GitHub可能要求使用个人访问令牌(PAT)：
1. 在GitHub中创建PAT: Settings > Developer settings > Personal access tokens
2. 生成新令牌，赋予适当权限
3. 使用此令牌替代密码

### 2. 推送被拒绝

如果远程仓库有您本地没有的更改，先拉取再推送：
```bash
git pull --rebase origin master
git push origin master
```

---

祝您项目发布顺利！如有疑问，欢迎参考[GitHub官方文档](https://docs.github.com/cn)。 